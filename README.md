# TRAC at 30: A Bibliometric Analysis of the TRAC Community

[![DOI](https://zenodo.org/badge/292529800.svg)](https://zenodo.org/badge/latestdoi/292529800)

This repository contains the R code and data for a bibliometric analysis of publications from the Theoretical Roman Archaeology Conference (TRAC) organisation. The data and RMarkdown document compruse the dat analysis for a paper entitled 'TRAC at 30: A Bibliometric Analysis of the TRAC Community'. The abstract of the paper is provided below:

## Abstract

*As TRAC approaches another milestone anniversary there is much to celebrate — a successful conference, a large body of publications and a thriving community. Part of this success stems from the unusually introspective and self-critical nature of the organisation. However, despite this tradition, there has been limited data-driven analysis of TRAC’s successes and failures. This paper uses bibliometric data from the corpus of TRAC publications over the last 30 years to analyse whether the organisation has achieved its aims. Alongside data from comparable journals, this research will also determine whether TRAC is ahead or behind the wider academic world. This paper provides insights into how diverse TRAC has become and how we might move forward in future.*

The full journal article, which is available as an Open Access publication, can be found on the TRAJ pages on the Open Library of Humanities platform ([link](https://doi.org/10.16995/traj.4344)).

## Reproducibility of research 

The bibliometric analysis for this article was undertaken using the R programming software (R Core Team 2018), specifically the *tidyr* (Wickham and Henry 2020) and *bibliometrix* packages (Aria and Cuccurullo 2017). The code was partly adapted from recent research undertaken by Schmidt and Marwick (2020). In order to make this research open and reproducible (e.g. Marwick 2017), the R code used for the analysis and visualizations from this paper (Supplementary file 2) and the data downloaded from Web of Science for both Britannia and the Journal of Social Archaeology were included (Supplementary file 3 and 4) as supplementary files to the publication and can be accessed here through this Github repository. In accordance with the TRAJ editorial policy, these files are offered under a Creative Commons licence (CC BY 4.0). 

## Data

The 'Data' folder includes the three files that were used in the compilation of this paper:

* 'trac_database.csv' - This .csv file contains a database of all TRAC publcations from the inception of the organisation until July 2020. For a list of all database fileds see Table 1 in the TRAJ article (link above). Tis file was compiled by the Author and is avaiable for reuse under a Creative Commons licence (CC BY 4.0)th a 

* 'jour_social.bib' - A bibtex file downloaded from the Web of Science database on 22.07.20, containing the articles from the Journal of Social Archaeology. This file was used to compare to data from the TRAC database in the latter parts of the paper.

* 'britannia.bib' - A bibtex file downloaded on from the Web of Science database 22.07.20, containing the articles from the Britannia journal. This file was used to compare to data from the TRAC database in the latter parts of the paper.

The TRAC Publication database will be updated on an annual basis (in April each year) to include all article published within the last year. A folder with the updated dataset, alongside an updated RMarkdown document will be included in the reprositry under 'database_update'. The folder label will include a datethat relates to the latest iteration of the update. 

## Further research

The TRAC Publication database will be updated on an annual basis (in April each year) to include all article published within the last year. A folder with the updated dataset, alongside an updated RMarkdown document will be included in the repository under 'database_update'. The folder label will include a date that relates to the latest iteration of the update. 

The first update was undertaken on the 05.04.21. The folder contains an updated database file (.csv) and an updated RMarkdown file (.rmd).

## References

* Aria, M. and Cuccurullo, C. 2017. Bibliometrix: An R-tool for comprehensive science mapping analysis. Journal of Informetrics 11(4): 959–975. DOI: https://doi.org/10.1016/j.joi.2017.08.007

* R Core Team. 2018. R: A Language and Environment for Statistical Computing. R Foundation for Statistical Computing. Vienna, Austria. Available at https://www.R-project.org/.

* Schmidt, S.C. and Marwick, B. 2020. Tool-Driven Revolutions in Archaeological Science. Journal of Computer Applications in Archaeology 3(1): 18–32. DOI: http://doi.org/10.5334/jcaa.29 

* Wickham, H. and Henry, L. 2020. tidyr: Tidy messy data. R package version 1.1.0. Available at https://CRAN.R-project.org/package=tidyr 
