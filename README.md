
# CNAqc <img src='man/figures/logo.png' align="right" height="139" />

<!-- badges: start -->

[![R-CMD-check](https://github.com/caravagnalab/CNAqc/workflows/R-CMD-check/badge.svg)](https://github.com/caravagnalab/CNAqc/actions)
[![pkgdown](https://github.com/caravagnalab/CNAqc/actions/workflows/pkgdown.yaml/badge.svg)](https://github.com/caravagnalab/CNAqc/actions/workflows/pkgdown.yaml)

[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-stable-green.svg)](https://www.tidyverse.org/lifecycle/#stable)
<!-- badges: end -->

`CNAqc` is a package that contains different methods to inspect the
quality, visualise and process allele-specific Copy Number Alteration
(CNA) calls generated from bulk sequencing of tumour samples, jointly
with tumour somatic mutations and other covariates.

Methods are available to integrate somatic mutation data with CNA
segments, tumour purity and ploidy assessment. The package provides
methods to estimate Cancer Cell Fractions (CCFs) normalizing tumour
allele frequencies for copy number states and tumour purity. The package
contains also statistical tests to identify patterns of
over-fragmentation of chromosome arms.

`CNAqc` is part of the `evoverse` set of [R
packages](https://caravagn.github.io/evoverse) to implement Cancer
Evolution analyses.

#### Citation

[![](https://img.shields.io/badge/doi-10.1101/2021.02.13.429885-red.svg)](https://doi.org/10.1101/2021.02.13.429885)

If you use `CNAqc`, please cite:

-   *A fully automated approach for quality control of cancer mutations
    in the era of high-resolution whole genome sequencing* Jacob
    Househam, William CH Cross and Giulio Caravagna. [biorXiv
    preprint](https://www.biorxiv.org/content/10.1101/2021.02.13.429885v1.full),
    2021

#### Help and support

## [![](https://img.shields.io/badge/GitHub%20Pages-https://caravagnalab.github.io/CNAqc/-yellow.svg)](https://caravagnalab.github.io/CNAqc)

### Installation

You can install the released version of `CNAqc` from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("caravagnalab/CNAqc")
```

------------------------------------------------------------------------

#### Copyright and contacts

Giulio Caravagna. Cancer Data Science (CDS) Laboratory.

[![](https://img.shields.io/badge/Email-gcaravagn@gmail.com-steelblue.svg)](mailto:gcaravagn@gmail.com)
[![](https://img.shields.io/badge/CDS%20Lab%20Github-caravagnalab-seagreen.svg)](https://github.com/caravagnalab)
[![](https://img.shields.io/badge/CDS%20Lab%20webpage-https://www.caravagnalab.org/-red.svg)](https://www.caravagnalab.org/)
