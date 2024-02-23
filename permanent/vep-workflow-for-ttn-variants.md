---
date: 2024-02-21
category: reference
stage: considering
tags:
  - programming
  - genetics
---

This is a workflow that was generated in part for the [ECG-prediction-of-TTN-variants](../permanent/ECG-prediction-of-TTN-variants.md) project.
This is written from the perspective of using `R` and `shell` scripts to analyze VCF files with the [Ensembl-VEP](https://useast.ensembl.org/info/docs/tools/vep/index.html) toolkit. 


```{r}
vcf_path <- fs::path("../data/Broad-AF-UIC-Cases-UIC0002.vcf")
```

This will allow the VCF file to be addended on to the pre-existing VCF essentially, with a new column of all the __consequences__ which are the results of the VEP analysis. 

```{bash}	
#| eval: false
vep --offline --vcf --input_file ../data/Broad-AF-UIC-Cases-UIC0002.vcf --output_file ../data/sample-vep.vcf  --everything
```

This can also be done in the form of a text file which has more "columnar" data for the consequences.

```{bash}	
#| eval: false
vep -i Broad-AF-UIC-Cases-UIC0002.vcf -o sample-vep.txt --offline --everything --fork 4
```

Both of these types of files that are direct outputs of the `vep` command can be filtered afterwards. 
This filtering process, using the `filter_vep` command, is done __after__ any plugins or additional annotation of consequences is done.

```{bash}
#| eval: false
filter_vep -i sample-vep.txt -o sample-filter.txt -filter "SYMBOL is TTN and SIFT != tolerated and PolyPhen != benign" --force
```

One of the relevant extensible parts of VEP is that it can be used with plugins. 
Some are built in, and some have to be referenced indirectly. 
The following sample is an example of using the LOFTEE plugin to help identify potential loss-of-function variants, either through early truncation or deletion. 

```{bash}
#| eval: false
vep -i Broad-AF-UIC-Cases-UIC0002.vcf -o sample-loftee.txt --fork 4 --cache --plugin LoF,loftee_path:/Users/asshah4/tools/loftee/,human_ancestor_fa:false --dir_plugin /Users/asshah4/tools/loftee/
```
