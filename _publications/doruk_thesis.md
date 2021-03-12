---
title: "Machine learning assisted intraoperative assessment of brain tumor margins using HRMAS NMR spectroscopy"
collection: publications
permalink: /publication/doruk_thesis
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2020-10-11
venue: 'PLOS Computational Biology'
paperurl: 'https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008184&rev=1'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Complete resection of the tumor is important for survival in glioma patients. Even if the gross total resection was achieved, left-over micro-scale tissue in the excision cavity risks recurrence. High Resolution Magic Angle Spinning Nuclear Magnetic Resonance (HRMAS NMR) technique can distinguish healthy and malign tissue efficiently using peak intensities of biomarker metabolites. The method is fast, sensitive and can work with small and unprocessed samples, which makes it a good fit for real-time analysis during surgery. However, only a targeted analysis for the existence of known tumor biomarkers can be made and this requires a technician with chemistry background, and a pathologist with knowledge on tumor metabolism to be present during surgery. Here, we show that we can accurately perform this analysis in real-time and can analyze the full spectrum in an untargeted fashion using machine learning. We work on a new and large HRMAS NMR dataset of glioma and control samples (n = 565), which are also labeled with a quantitative pathology analysis. Our results show that a random forest based approach can distinguish samples with tumor cells and controls accurately and effectively with a median AUC of 85.6% and AUPR of 93.4%. We also show that we can further distinguish benign and malignant samples with a median AUC of 87.1% and AUPR of 96.1%. We analyze the feature (peak) importance for classification to interpret the results of the classifier. We validate that known malignancy biomarkers such as creatine and 2-hydroxyglutarate play an important role in distinguishing tumor and normal cells and suggest new biomarker regions. The code is released at http://github.com/ciceklab/HRMAS_NC.

### To cite, use the following bibtex entry:
```
@article{10.1371/journal.pcbi.1008184,
    author = {Cakmakci, Doruk AND Karakaslar, Emin Onur AND Ruhland, Elisa AND Chenard, Marie-Pierre AND Proust, Francois AND Piotto, Martial AND Namer, Izzie Jacques AND Cicek, A. Ercument},
    journal = {PLOS Computational Biology},
    publisher = {Public Library of Science},
    title = {Machine learning assisted intraoperative assessment of brain tumor margins using HRMAS NMR spectroscopy},
    year = {2020},
    month = {11},
    volume = {16},
    url = {https://doi.org/10.1371/journal.pcbi.1008184},
    pages = {1-14},
    number = {11},
    doi = {10.1371/journal.pcbi.1008184}
}
```