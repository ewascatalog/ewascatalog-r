# ewascatalog
This package allows users to query the EWAS Catalog from R.

## Functions
ewascatalog - function to query the EWAS Catalog.

## Installation
install.packages("devtools")
library(devtools)
install_github("jrs95/ewascatalog")
library(ewascatalog)

## Examples
\\# CpG
res <- ewascatalog(cpgquery="cg00029284")

\\# Region
res <- ewascatalog(regionquery="6:15000000-25000000")

\\# Gene
res <- ewascatalog(genequery="FTO")

\\# Trait
res <- ewascatalog(traitquery="body mass index")

