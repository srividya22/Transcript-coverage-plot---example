---
title: "BinningPlotting"
author: "Zaki Fadlullah"
date: "4 April 2016"
output: pdf_document
---

## Drawing a 5' to 3' transcript plot


```r
# Generate example coverage data for gene1 (g1)
g1 <- round(
  c(rnorm(866, mean=100),
    rnorm(11, mean=70),
    rnorm(30, mean=10),
    rnorm(7, mean=45),
    rnorm(30, mean=0, sd=0),
    rnorm(56, mean=5)))
head(g1)
```

```
## [1]  99 101 100  98  98 100
```

```r
#length(g1)
```



