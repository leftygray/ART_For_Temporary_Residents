# Impact of providing ART to PLHIV who are ineligible for health care

This project uses a simple analysis to calculate the impact of providing anti-retroviral therapy (ART) to people living with HIV (PLHIV) in Australia who are medicare ineligible. The analysis uses data from the Australian HIV Observational Database Temporary Residents Access Study (ATRAS). 

**Author:** Richard T. Gray

**Affiliation:** [_The Kirby Institute_](https://kirby.unsw.edu.au/), The University of New South Wales, Sydney NSW 2052, Australia

## Aims

The aim of these calculations is to estimate the number of new HIV infections that occur through transmission from Medicare ineligible people to their sexual partners, the cost of providing ART to the Medicare ineligible population, and the potential future cost of providing treatment to partners of Medicare ineligibles who become infected. 

## Code

The R code for these calculations is available in two Rmarkdown files:

* Medicare_Ineligibles.rmd — file to produce all the results for the second ATRAS report ([released March 2015](https://kirby.unsw.edu.au/publications/australian-hiv-observational-database-temporary-residents-access-study-atras-mar-2015)).

* Medicare_Ineligibles_manuscript.rmd. Modified version of Medicare_ineligibles.rmd to produce a manuscript suitable for submission to a journal. 

Both documents are written in dynamic format using R markdown v2 within R studio 0.98.1056 (using R version 3.1.2). Plots are created using the package ggplot2. Further details are available in the associated R markdown files which also contains the R code to produce all the results separately when the markdown is run. Code blocks are suppressed in the output documents. 
Other files in the repository are support files to produce the final output documents. 