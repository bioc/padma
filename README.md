# padma: Individualized multi-omic pathway deviation scores using multiple factor analysis

<img src="inst/logos/hex_padma_v2.png" align="right" width="200" />


The *padma* package can be installed as follows:

```
library(devtools)
devtools::install_github("andreamrau/padma")
library(padma)
```

*padma* uses multiple factor analysis to calculate individualized pathway-centric scores of deviation with respect to the sampled population based on multi-omic assays (e.g., RNA-seq, copy number alterations, methylation, etc). Graphical and numerical outputs are provided to identify highly aberrant individuals for a particular pathway of interest, as well as the gene and omics drivers of aberrant multi-omic profiles.

### Reference

Rau et al. (2019) Individualized multi-omic pathway deviation scores using multiple factor analysis. bioRxiv, doi: https://doi.org/10.1101/827022.