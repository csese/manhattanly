[![Travis-CI Build Status](https://travis-ci.org/sahirbhatnagar/manhattanly.svg?branch=master)](https://travis-ci.org/sahirbhatnagar/manhattanly)


# manhattanly

The goal of manhattanly is to ...

![](http://i.imgur.com/oTrElAb.gif)

## Installation

You can install manhattanly from github with:

```R
install.packages("devtools")
devtools::install_github("sahirbhatnagar/manhattanly")
```

## Example

This is a basic example which shows you how to solve a common problem:

```R
library(manhattanly)
manhattanly(HapMap, snp = "SNP", gene = "GENE")
```

## Credit

This package is inspired by the [`qqman`](https://github.com/stephenturner/qqman) by [Stephen Turner](http://stephenturner.us/). The pre-processing of the data in the `manhattanly` package is based on the `qqman::manhattan` and `qqman::qq` functions. 

The splitting of the tasks into data pre-processing and plot rendering is inspired by the [`heatmaply`](https://github.com/talgalili/heatmaply) package by [Tal Galili](http://www.r-statistics.com/)


## Related Work

* [`qqman`](https://github.com/stephenturner/qqman)
* [`D3ManhattanPlots`](https://github.com/nstrayer/D3ManhattanPlots)






## Contact

* Issues: <https://github.com/sahirbhatnagar/manhattanly/issues>
* Pull Requests: <https://github.com/talgalili/heatmaply/>
* e-mail: <sahir.bhatnagar@gmail.com>


## Latest news

You can see the most recent changes to the package in the [NEWS.md file](https://github.com/sahirbhatnagar/manhattanly/blob/master/NEWS.md)




## Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.