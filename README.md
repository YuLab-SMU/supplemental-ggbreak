# supplemental-ggbreak
This repo contains source code and data to produce Supplementary Material.

+ supplementary.Rmd: R Markdown file to compile the PDF

+ supplementary.pdf: Supplemental Material, the PDF

+ header.tex: LaTeX packages that used to compile the PDF

+ 7MWE_A.csv: the amino acid hydrophobicity or hydrophilicity scales output of human E3 ubiquitin-protein ligase HUWE1 Chain A(NCBI_id:7MWE_A) using Expasy-Protscale with default parameters.

+ gp200.nwk: newick text of gp200 tree was published on https://europepmc.org/article/MED/21113103.

+ GCST90007012_buildGRCh37.tsv : SNP data was collected from GWAS Catalog and published on https://www.nature.com/articles/s42003-020-01416-z.

+ data1.txt: microbe relative abundance data was published on https://www.sciencedirect.com/science/article/abs/pii/S0048969719352659.

+ sigdata.rda: significant levels of microbe relative abundance data was published on https://www.sciencedirect.com/science/article/abs/pii/S0048969719352659.

To compile the supplemental_file.pdf, please run the following command in R:

```
rmarkdown::render('supplementary.Rmd')
```
Here is the output of `devtools::session_info()` on the system on which the document was compiled:
```
# - Session info ----------------------------------------
#     setting  value
# version  R version 4.1.1 (2021-08-10)
# os       Windows 10 x64
# system   x86_64, mingw32
# ui       RStudio
# language (EN)
# collate  Chinese (Simplified)_China.936
# ctype    Chinese (Simplified)_China.936
# tz       Asia/Taipei
# date     2021-09-07
# 
# - Packages ----------------------------------------------------------------------------------------------------
#     package      * version date       lib source
# ape            5.5     2021-04-25 [1] CRAN (R 4.1.1)
# aplot          0.0.7   2021-09-01 [1] CRAN (R 4.1.1)
# bookdown       0.24    2021-09-02 [1] CRAN (R 4.1.1)
# cachem         1.0.6   2021-08-19 [1] CRAN (R 4.1.1)
# callr          3.7.0   2021-04-20 [1] CRAN (R 4.1.1)
# cli            3.0.1   2021-07-17 [1] CRAN (R 4.1.0)
# colorspace     2.0-2   2021-06-24 [1] CRAN (R 4.1.1)
# cowplot        1.1.1   2020-12-30 [1] CRAN (R 4.1.1)
# crayon         1.4.1   2021-02-08 [1] CRAN (R 4.1.1)
# desc           1.3.0   2021-03-05 [1] CRAN (R 4.1.1)
# devtools       2.4.2   2021-06-07 [1] CRAN (R 4.1.1)
# digest         0.6.27  2020-10-24 [1] CRAN (R 4.1.1)
# dplyr          1.0.7   2021-06-18 [1] CRAN (R 4.1.0)
# ellipsis       0.3.2   2021-04-29 [1] CRAN (R 4.1.0)
# evaluate       0.14    2019-05-28 [1] CRAN (R 4.1.1)
# fansi          0.5.0   2021-05-25 [1] CRAN (R 4.1.1)
# farver         2.1.0   2021-02-28 [1] CRAN (R 4.1.1)
# fastmap        1.1.0   2021-01-25 [1] CRAN (R 4.1.1)
# fs             1.5.0   2020-07-31 [1] CRAN (R 4.1.1)
# generics       0.1.0   2020-10-31 [1] CRAN (R 4.1.1)
# ggbreak      * 0.0.4   2021-08-14 [1] CRAN (R 4.1.1)
# ggfun          0.0.3   2021-08-17 [1] CRAN (R 4.1.1)
# ggplot2      * 3.3.5   2021-06-25 [1] CRAN (R 4.1.0)
# ggplotify      0.1.0   2021-09-02 [1] CRAN (R 4.1.1)
# ggtree       * 3.0.4   2021-08-22 [1] Bioconductor
# glue           1.4.2   2020-08-27 [1] CRAN (R 4.1.1)
# gridGraphics   0.5-1   2020-12-13 [1] CRAN (R 4.1.1)
# gtable         0.3.0   2019-03-25 [1] CRAN (R 4.1.1)
# htmltools      0.5.2   2021-08-25 [1] CRAN (R 4.1.1)
# jsonlite       1.7.2   2020-12-09 [1] CRAN (R 4.1.1)
# knitr          1.33    2021-04-24 [1] CRAN (R 4.1.1)
# labeling       0.4.2   2020-10-20 [1] CRAN (R 4.1.0)
# lattice        0.20-44 2021-05-02 [1] CRAN (R 4.1.1)
# lazyeval       0.2.2   2019-03-15 [1] CRAN (R 4.1.1)
# lifecycle      1.0.0   2021-02-15 [1] CRAN (R 4.1.1)
# magrittr       2.0.1   2020-11-17 [1] CRAN (R 4.1.1)
# memoise        2.0.0   2021-01-26 [1] CRAN (R 4.1.1)
# munsell        0.5.0   2018-06-12 [1] CRAN (R 4.1.1)
# nlme           3.1-152 2021-02-04 [1] CRAN (R 4.1.1)
# patchwork    * 1.1.1   2020-12-17 [1] CRAN (R 4.1.1)
# pillar         1.6.2   2021-07-29 [1] CRAN (R 4.1.1)
# pkgbuild       1.2.0   2020-12-15 [1] CRAN (R 4.1.1)
# pkgconfig      2.0.3   2019-09-22 [1] CRAN (R 4.1.1)
# pkgload        1.2.1   2021-04-06 [1] CRAN (R 4.1.1)
# plyr           1.8.6   2020-03-03 [1] CRAN (R 4.1.1)
# prettyunits    1.1.1   2020-01-24 [1] CRAN (R 4.1.1)
# processx       3.5.2   2021-04-30 [1] CRAN (R 4.1.1)
# ps             1.6.0   2021-02-28 [1] CRAN (R 4.1.1)
# purrr          0.3.4   2020-04-17 [1] CRAN (R 4.1.1)
# R6             2.5.1   2021-08-19 [1] CRAN (R 4.1.1)
# Rcpp           1.0.7   2021-07-07 [1] CRAN (R 4.1.1)
# remotes        2.4.0   2021-06-02 [1] CRAN (R 4.1.1)
# reshape        0.8.8   2018-10-23 [1] CRAN (R 4.1.1)
# reshape2       1.4.4   2020-04-09 [1] CRAN (R 4.1.1)
# rlang          0.4.11  2021-04-30 [1] CRAN (R 4.1.1)
# rmarkdown      2.10    2021-08-06 [1] CRAN (R 4.1.1)
# rprojroot      2.0.2   2020-11-15 [1] CRAN (R 4.1.1)
# rstudioapi     0.13    2020-11-12 [1] CRAN (R 4.1.1)
# scales         1.1.1   2020-05-11 [1] CRAN (R 4.1.1)
# sessioninfo    1.1.1   2018-11-05 [1] CRAN (R 4.1.1)
# stringi        1.7.4   2021-08-25 [1] CRAN (R 4.1.1)
# stringr        1.4.0   2019-02-10 [1] CRAN (R 4.1.1)
# testthat       3.0.4   2021-07-01 [1] CRAN (R 4.1.1)
# tibble         3.1.4   2021-08-25 [1] CRAN (R 4.1.1)
# tidyr          1.1.3   2021-03-03 [1] CRAN (R 4.1.1)
# tidyselect     1.1.1   2021-04-30 [1] CRAN (R 4.1.1)
# tidytree       0.3.4   2021-05-22 [1] CRAN (R 4.1.1)
# treeio       * 1.16.2  2021-08-17 [1] Bioconductor
# usethis        2.0.1   2021-02-10 [1] CRAN (R 4.1.1)
# utf8           1.2.2   2021-07-24 [1] CRAN (R 4.1.1)
# vctrs          0.3.8   2021-04-29 [1] CRAN (R 4.1.1)
# withr          2.4.2   2021-04-18 [1] CRAN (R 4.1.1)
# xfun           0.25    2021-08-06 [1] CRAN (R 4.1.1)
# yaml           2.2.1   2020-02-01 [1] CRAN (R 4.1.0)
# yulab.utils    0.0.2   2021-08-16 [1] CRAN (R 4.1.1)
```
