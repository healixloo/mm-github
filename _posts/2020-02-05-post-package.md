---
title: "Packages"
categories:
  - Packages
tags:
  - Development
  - scRNAseq
  - scCOOLseq
---

Package `Development` has been shared in [GitHub](https://github.com/healixloo/Development).

```html
Installation:
devtools::install_github("healixloo/Development")

Vignettes:
res2<-read.csv(system.file("extdata", "res2.csv", package = "Development"),head=T)
mm9Chromosome<-read.csv(system.file("extdata", "mm9Chromosome.csv", package = "Development"),head=T)
library(pROC)
pdf("test.pdf")
p9<-roc_calculate(res2,mm9Chromosome,J_name="mm9Chromosome")
dev.off()
```

