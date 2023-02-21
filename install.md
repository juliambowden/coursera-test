---
title: Install
---

CoGAPS is a bioconductor package and so the release version can be installed as follows:

source("https://bioconductor.org/biocLite.R")
biocLite("CoGAPS")
The most up-to-date version of CoGAPS can be installed directly from the FertigLab Github Repository:

## Method 1 using biocLite
biocLite("FertigLab/CoGAPS", dependencies = TRUE, build_vignettes = TRUE)

## Method 2 using devtools package
devtools::install_github("FertigLab/CoGAPS")
There is also an option to install the development version of CoGAPS, while this version has the latest experimental features, it is not guaranteed to be stable.

## Method 1 using biocLite
biocLite("FertigLab/CoGAPS", ref="develop", dependencies = TRUE, build_vignettes = TRUE)

## Method 2 using devtools package
devtools::install_github("FertigLab/CoGAPS", ref="develop")
