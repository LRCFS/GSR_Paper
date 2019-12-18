[![DOI](https://zenodo.org/badge/228665895.svg)](https://zenodo.org/badge/latestdoi/228665895)

A scientometric approach using gunshot residue (GSR) literature as an example
=============================================================================

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

Quickstart
----------

To generate the keyword trending plot and Gephi input files run:

    Rscript ScopusSearch.R

This creates a `KeywordTrend.png` plot and `GephiAuthor.csv` 
`GephiListAuthorLastYear.csv` files.
    
To generate the subject area boxplot run:

    Rscript CitationCode.R

This creates a `SubjectBoxplot.png` file.

