# Impact of providing ART to PLHIV who are ineligible for Medicare in Australia

This project uses a simple analysis to calculate the impact of providing anti-retroviral therapy (ART) to people living with HIV (PLHIV) in Australia who are medicare ineligible. The analysis uses data from the Australian HIV Observational Database Temporary Residents Access Study (ATRAS). 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.825366.svg)](https://doi.org/10.5281/zenodo.825366)

All calculations are primarily conducted using R with associated packages (gridExtra; knitr; Hmisc; Formula; survival; lattice; RColorBrewer; scale; ggplot2; readxl; tidyr; dplyr; readr) see 
release notes for details. Please report an issue if you want to run the code or contact Rgray@kirby.unsw.edu.au.

**Repository owner:** Richard T. Gray

**ORCID ID:** orcid.org/0000-0002-2885-0483

**Affiliation:** [_The Kirby Institute_](https://kirby.unsw.edu.au/), The University of New South Wales, Sydney NSW 2052, Australia

## Aims

The aim of these calculations is to estimate the number of new HIV infections that occur through transmission from Medicare ineligible people to their sexual partners, the cost of providing ART to the Medicare ineligible population, and the potential future cost of providing treatment to partners of Medicare ineligibles who become infected. 

## Code

The R code for this project is contained in the R markdown file **Medicare_Ineligibles.Rmd**. This file contains all the code to perform the model simulations and calculations and to produce all the figures and results. This document is written in dynamic format using R markdown within Rstudio with R and associated packages. Plots are created using the package ggplot2. Specific details can be found within the R markdown file. By running this file all the results and figures can be reproduced and an associated Microsoft Word document is created. Code blocks containing important details of the calculations and input parameters are suppressed in the output document. Other files in the repository are support files to produce the final output documents.

A final version of the resulting Word document is available in the docs/ folder: **docs/Medicare_ineligibles-Report.docx**. This document with the associated R markdown file contain all the methodological details, equations, input parameters and references for the analyses and act as [supplementary material](https://github.com/leftygray/ART_For_Temporary_Residents/tree/master/docs) for the publications listed below. 

## Publications

The following publications are associated with this project and used the code in this repository to generate all/some of the results and figures.

- The Kirby Institute. The Australian HIV Observational Database Temporary Residents Access Study (ATRAS) Two year follow-up. 2015. The Kirby Institute, UNSW Australia, Sydney NSW 2052.
  - [Released March 2015](https://kirby.unsw.edu.au/publications/australian-hiv-observational-database-temporary-residents-access-study-atras-mar-2015) and available from the Kirby Institute website ([pdf](https://kirby.unsw.edu.au/sites/default/files/AHOD_ATRAS%20Report%20Vol.%202%202015.pdf))
  - The results in this report were produced using [version 2.1](https://github.com/leftygray/ART_For_Temporary_Residents/releases/tag/v2.1); doi:[10.5281/zenodo.48990](https://doi.org/10.5281/zenodo.48990)
<br></br>
- RT Gray, J Watson, AJ Cogle, DE Smith, JF Hoy, LA Bastian, R Finlayson, FM Drummond, B Whittaker, MG Law, K Petoumenos. Funding ART for HIV-positive residents in Australia prevents transmission and is inexpensive. Sexual Health. In Press.
  - Submitted paper based on [version 2.1](https://github.com/leftygray/ART_For_Temporary_Residents/tree/v2.1); doi:[10.5281/zenodo.48990](https://doi.org/10.5281/zenodo.48990)
  - Final paper based on [version 2.2.1](https://github.com/leftygray/ART_For_Temporary_Residents/releases/tag/v2.2.1); doi:[10.5281/zenodo.825366](https://doi.org/10.5281/zenodo.573028)
  - The supplementary material for this paper consists of the files Medicare_Ineligibles.Rmd, docs/Medicare_Ineligibles-Report.docx, and docs/Medicare_Ineligibles-Supplementary_results.docx
  - Raw result files are available on request (Rgray@kirby.unsw.edu.au)
