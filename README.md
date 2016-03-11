# singleCellRNASeqMouseDeng2014
Deng et al 2014 data package, check the paper [here](http://www.ncbi.nlm.nih.gov/pubmed/24408435).

To load the data 

```
library(singleCellRNASeqMouseDeng2014)
counts <- exprs(Deng2014MouseESC)
meta_data <- pData(Deng2014MouseESC)
gene_names <- rownames(counts)

```
