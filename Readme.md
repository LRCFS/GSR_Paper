[![DOI](https://zenodo.org/badge/228665895.svg)](https://zenodo.org/badge/latestdoi/228665895)

A scientometric approach using gunshot residue (GSR) literature as an example
=============================================================================

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/LRCFS/GSR_Paper/master?urlpath=%2Frstudio)

This repository contains the R scripts used to process literature 
searches performed Scopus and supports the results found in the
paper:

Sobriera et al. *Reviewing research trends - a scientometric approach using gunshot residue (GSR) literature as an example* (2020).

Requirements
------------

The scripts were written for R 3.6.1 and require the following 
libraries:

    tidyverse
    ggplot2
    maps
    countrycode
    RColorBrewer

Quickstart
----------

To generate the keyword trending plot and Gephi input files run:

    Rscript ScopusSearch.R

This creates the `Fig2_CountryCounts.png`, `Fig5_KeywordTrend.png` plots and the `GephiAuthor.csv`, 
`GephiListAuthorLastYear.csv` and `Table1_full.txt` files.
    
To generate the subject area boxplot run:

    Rscript CitationCode.R

This creates a `Fig4_SubjectBoxplot.png` file.

**MyBinder**

Alternatively, click the "launch binder" button at the top of the this readme to open
an interactive RStudio session hosted by [mybinder.org](https://mybinder.org/).

