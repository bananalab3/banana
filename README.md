
<!-- README.md is generated from README.Rmd. Please edit that file -->

<img src="data/figure/Title.png" width="100%" style="margin-top: 20px;" />

<!-- badges: start -->

[![R
\>3.5](https://img.shields.io/badge/R-%3E3.5-success.svg)](https://www.r-project.org/)
<a href='#devtools'>![installed with
devtools](https://img.shields.io/badge/installed%20with-devtools-blueviolet.svg)</a>
[![WebServer](https://img.shields.io/badge/Web_Server-MMEASE-blue)](http://idrblab.org/mmease2025/)
<!-- badges: end -->

# How to Use `banana`?

## Contents

- [Overview](#overview)
- [Installation](#installation)
- [Example Data](#example-data)
- [Usage and Examples](#usage-and-examples)

## Overview

Metabolomics closest to the phenotype is shifting to the single-cell
level (SCM), which is a powerful tool for studying cellular
heterogeneity by providing insight into the differences be-tween
individual cells. Because analytical workflow of single-cell
metabolomics (SCM) in-cludes various processes, a standardized and
transparent pipeline is essential to connect the raw data to biological
interpretation especially for non-bioinformatic researchers. However, a
uni-fied tool to provide the entire workflow of SCM is still
lacking.<br><br>In this study, MMEASE was updated to its 2.0 version by
advancing from bulk metabolomics to the single-cell metabolom-ics, which
realize a comprehensive analytical workflow of SCM for the first time.
Specifically, MMEASE 2.0 is a unique tool in SCM by (a) providing the
most comprehensive workflow of data processing, (b) realizing
systematical functions of analyzing both metabolic heterogeneity and
functional heterogeneity, and (c) significantly enhancing the capability
of metabolite an-notation with biological interpretations using tandem
spectra.<br><br>In summary, MMEASE 2.0 pro-vides an indispensable online
service of whole analytical workflow in SCM. MMEASE 2.0 is freely
accessible at
<a href="https://idrblab.org/mmease2025/">http://idrblab.org/mmease2025</a>.

## Installation

You can install the development version of banana from
[GitHub](https://github.com/) with:

``` r
if (!requireNamespace("devtools", quietly = TRUE))
    install.packages("devtools")
devtools::install_github("bananalab3/banana")
```

## Example Data

You can use the example data provided in `banana` to try it out.

**Example single-cell metabolomic data**
([Download](https://iboalab.cn/mmease2025/MTBLS78_co_culture.csv)): As
shown in the sample data, cell name, cell classes, cell types, and batch
information are required in the first four columns of the input file. In
the following columns, the raw peak intensities across all cells are
further provided. Unique metabolite IDs or peaks are listed in the first
row of the csv file.

## Usage and Examples

For the usage and examples of `banana`, users can refer to the vignette
“How to Use `banana`” built in the package.
