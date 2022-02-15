---
tags: [r, stats]
---

# Approach

This is a development / exploration of what classes would be needed and what characteristics would be required for an effective causal modeling approach.

```mermaid
graph TD

	1a(y <- x)
	1b(y <- c)
	1c(y <- m)
	1d(x <- c)
	1e(m <- x)
	2(y <- x <br> y <- c <br> y <- m <br> x <- c <br> m <- x )
	3(y <- x + m + c <br> y <- x + c <br> m <- x + c)
	4("y <- exposure(x) + confounder(c) + mediator(m)")
	5(y1 <- x1 + x2 + m + ... <br> y2 <- x2 + c + m)

	subgraph a [Atomic relationships to Relationship Stack]
	1a --> 2
	1b --> 2
	1c --> 2
	1d --> 2
	1e --> 2
	end
	
	2 -- Formula List --> 3
	3 -- Compact Formula List --> 4
	4 -- Formula Map --> 5
	
```

# Classes
## Atomic Relationships

```r
y ~ x
```

Requirements:
- pattern would only be for a single relationship between independent and dependent variables
- there should be no other terms included

## Relationship Stacks

```r
y ~ x
y ~ c
y ~ m
x ~ c
m ~ x
```

Requirements:
- specific/special list classification 
- each list item would need to be an atomic relationship

## Formula Lists

```r
y1 ~ ...
y2 ~ ...
```
## Compacted Formula Lists
```r
y ~ X(x) + C(c) + M(m)
```

## Formula Maps

```r
y1 ~ ...
y2 ~ ...
```