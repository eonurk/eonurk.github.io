---
title: "[Preprint] cinaR: A comprehensive R package for the differential analyses and functional interpretation of ATAC-seq data"
collection: publications
permalink: /publication/cinar
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2020-10-11
venue: 'bioaRxiv'
paperurl: 'https://www.biorxiv.org/content/10.1101/2021.03.05.434143v2'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Summary ATAC-seq is a frequently used assay to study chromatin accessibility levels. Differential chromatin accessibility analyses between biological groups and functional interpretation of these differential regions are essential in ATAC-seq data analyses. Although distinct methods and analyses pipelines are developed for this purpose, a stand-alone R package that combines state-of-the art differential and functional enrichment analyses pipelines is missing. To fill this gap, we developed cinaR (Chromatin Analyses in R), which is a single wrapper function and provides users with various data analyses and visualization options, including functional enrichment analyses with gene sets curated from multiple sources.

Availability and implementation cinaR is an R/CRAN package which is under GPL-3 License and its source code is freely accessible at https://CRAN.R-project.org/package=cinaR.

Gene sets are available at https://CRAN.R-project.org/package=cinaRgenesets.

Bone marrow ATAC-seq data is available at https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE165120.


### To cite, use the following bibtex entry:
```
@article {Karakaslar2021.03.05.434143,
	author = {Karakaslar, E Onur and Ucar, Duygu},
	title = {cinaR: A comprehensive R package for the differential analyses and functional interpretation of ATAC-seq data},
	elocation-id = {2021.03.05.434143},
	year = {2021},
	doi = {10.1101/2021.03.05.434143},
	publisher = {Cold Spring Harbor Laboratory},
	URL = {https://www.biorxiv.org/content/early/2021/03/08/2021.03.05.434143.1},
	eprint = {https://www.biorxiv.org/content/early/2021/03/08/2021.03.05.434143.1.full.pdf},
	journal = {bioRxiv}
}
```