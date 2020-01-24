# Data package of Tripanosoma brunei RNA-seq

## Sources

* Original data source: [GSE100895](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE100895)
* Original citation:
  * Müller LSM, Cosentino RO, Förstner KU, Guizetti J et al. Genome organization and DNA accessibility control antigenic variation in trypanosomes. Nature 2018 Nov;563(7729):121-125. PMID: 30333624
  
## Usage

Install, import and load the data set
```R
devtools::install_github('ttdtrang/data-rnaseq-Tbru')
library(data-rnaseq-Tbru)
data(tbru.rnaseq)
dim(tbru.rnaseq@assayData$exprs)
```
