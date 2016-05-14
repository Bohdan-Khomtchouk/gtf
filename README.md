[![Travis-CI Build Status](https://travis-ci.org/Bohdan-Khomtchouk/gtf.svg?branch=master)](https://travis-ci.org/Bohdan-Khomtchouk/gtf)
[![Coverage Status](https://coveralls.io/repos/github/Bohdan-Khomtchouk/gtf/badge.svg?branch=master)](https://coveralls.io/github/Bohdan-Khomtchouk/gtf?branch=master)
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)
# gtf

R data package that provides gene transfer format files for commonly studied model organisms.  These files include annotations of both coding and non-coding genes. The .gtf file format is described here: http://www.gencodegenes.org/gencodeformat.html.  

`gtf` is currently used by at least one existing R package: `geneXtendeR`. 

### Installation instructions

You can install the current GitHub version using the [devtools](https://github.com/hadley/devtools) package and the following command in R:
```R
devtools::install_github("Bohdan-Khomtchouk/gtf")
```
And then:
```R
library(gtf)
```
