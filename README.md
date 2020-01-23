# Data package of Tripanosoma brunei RNA-seq

## Sources

* Original data source: [GSE100895](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE100895)
* Original citation:
  * Müller LSM, Cosentino RO, Förstner KU, Guizetti J et al. Genome organization and DNA accessibility control antigenic variation in trypanosomes. Nature 2018 Nov;563(7729):121-125. PMID: 30333624
  
## [tentative] Usage

```R
library(data-rnaseq-Tbru)
cnt = tbru.rnaseq@assayData$exprs
dim(cnt)
```
