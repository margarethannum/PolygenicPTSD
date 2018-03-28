
<!-- README.md is generated from README.Rmd. Please edit that file -->
polygenicPTSD
=============

The goal of polygenicPTSD is to make an easy-to-use package for multi-center sites in the PGC-PTSD working group to conduct analysis on the interaction between PTSD and BP Polygenic Risk Score (PRS) in predicting various BP outcomes. It includes functions to ensure data has appropriate variables required for analysis, creates new variables which categorizes continues BP into categorical hypertension outcomes based on old and new AHA criteria, stratifies data by ancestry, runs linear regressions on continuous BP outcomes and generalized linear models on categorical hypertension outcomes, and more.

Installation
------------

You can install polygenicPTSD from github with:

``` r
# install.packages("devtools")
devtools::install_github("margarethannum/PolygenicPTSD")
```

Example
-------

This is a basic example which shows you how to solve a common problem:

``` r
## Load example simulated data
#data("merged_example")

## Create dataframe with new categorical variables necessary for analysis
#classed <- htn_outcome_classify(merged_example)

## Stratify based on ancestry and test to see if there is a significant difference between old vs new AHA classifications within ancestry; saves results

#setwd("~/results/")


## Run linear regression analysis on continuous outcomes; saves results
#polygenicPTSD_contin(classed)
```
