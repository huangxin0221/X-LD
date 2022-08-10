# X-LD
R package {XLD} has been developed to compute for complex LD patterns for small sample sizes.

## Installation

```r
# This is an R console
# 1. First, make sure the following R packages are installed
install.packages(c("ggplot2","zip"))
# 2. Then, download the source codes of X-LD (XLD_0.1.0.tar.gz), and install it.
install.packages("XLD_0.1.0.tar.gz",type="source",repos=NULL)
```

## Usage
```r
# This is an R console
# 1. load package
library(XLD)
# 2. help document 
help("X_LD")
# 3. run the examples (test.bed, test.bim, and test.fam)
X_LD(input="test",output="test",population_type = "inbred",autosome=5)
```
