[![Travis-CI Build Status](https://travis-ci.org/Bohdan-Khomtchouk/gtf.svg?branch=master)](https://travis-ci.org/Bohdan-Khomtchouk/gtf)
[![MIT license](http://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)
[![GitHub version](https://badge.fury.io/gh/Bohdan-Khomtchouk%2Fgtf.svg)](https://badge.fury.io/gh/Bohdan-Khomtchouk%2Fgtf)
# gtf

R data package that provides gene transfer format files for commonly investigated model organisms in ChIP-seq studies.  These files include annotations of both coding and non-coding genes. The .gtf file format is described here: http://www.gencodegenes.org/gencodeformat.html.  

`gtf` is currently used by at least one existing R package: `geneXtendeR`. 

### Installation instructions

You can install the current GitHub version using the [devtools](https://github.com/hadley/devtools) package and the following command in R:
```R
if (!require("devtools")) install.packages("devtools")
devtools::install_github("Bohdan-Khomtchouk/gtf")
```
And then:
```R
library(gtf)
```

Note: Certain older version of R may (or may not) prompt you that:

```R
> install_github("Bohdan-Khomtchouk/gtf")
Downloading GitHub repo Bohdan-Khomtchouk/gtf@master
from URL https://api.github.com/repos/Bohdan-Khomtchouk/gtf/zipball/master
Installing gtf
‘BiocInstaller’ must be installed for this functionality.
Would you like to install it?

1: Yes
2: No

Selection: 1
Error in loadNamespace(name) : there is no package called ‘BiocInstaller’
In addition: Warning message:
package ‘BiocInstaller’ is not available (for R version 3.2.1) 
```R

In such cases, first do:

```R
source("http://bioconductor.org/biocLite.R")
biocLite("BiocInstaller")
```R


