---
tags: [r, programming, stats, epi]
---

# Formulas 

In the traditional formula, as seen in `R`, the capabilities include:

- directly identifies the independent and dependent variables 
- models to be built/informed
- data selection (e.g. vectors/columns) along with data transformation
- terms can be modified and some interaction/relationships can be implemented

The capabilities that traditional formulas are missing:

- variable roles within relationships of formulas
- nested/grouped formulas that represent a modeling concept (e.g. mediation, confounding)
- stratification of data
- hierarchical formulas (such as random effects)
- formula expansions and combinations

# Structure

This diagram is to help identify the structures needed in the development of an improved formula system.

```mermaid
classDiagram
direction TB

class FormulaList {
	list~character~ labels
	list~character~ roles
	list~character~ groups
	list_of_formulas(~formula_vctr~) ~list_of_formulas~
	list_of_formulas(list~formula~) ~list_of_formulas~
}

class FormulaVector {
	list~character~ labels
	list~character~ roles
	list~character~ groups
	list~character~ operations
	list~term_rcrd~ terms
	formula_vctr(~term_rcrd~) ~formula_vctr~
	formula_vctr(~formula~) ~formula_vctr~
}

class TermRecord {
	character term
	character roles
	character groups
	character operations
	character labels
	term_rcrd(~character~) ~term_rcrd~
	term_rcrd(~formula~) ~term_rcrd~
}

FormulaList <|-- FormulaVector
FormulaVector "1" <|-- "1..*" TermRecord
```

