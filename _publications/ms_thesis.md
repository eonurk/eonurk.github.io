---
title: "Predicting Carbon Spectrum in Heteronuclear Single Quantum Coherence Spectroscopy for Online Feedback During Surgery"
collection: publications
permalink: /publication/10.1109:TCBB.2019.2920646
date: 2020-06-01
venue: 'IEEE/ACM Transactions on Computational Biology'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8730423/authors#authors'
---
1 H High-Resolution Magic Angle Spinning (HRMAS) Nuclear Magnetic Resonance (NMR) is a reliable technology used for detecting metabolites in solid tissues. Fast response time enables guiding surgeons in real time, for detecting tumor cells that are left over in the excision cavity. However, severe overlap of spectral resonances in 1D signal often render distinguishing metabolites impossible. In that case, Heteronuclear Single Quantum Coherence Spectroscopy (HSQC) NMR is applied which can distinguish metabolites by generating 2D spectra (1H- 13 C). Unfortunately, this analysis requires much longer time and prohibits real time analysis. Thus, obtaining 2D spectrum fast has major implications in medicine. In this study, we show that using multiple multivariate regression and statistical total correlation spectroscopy, we can learn the relation between the 1 H and 13 C dimensions. Learning is possible with small sample sizes and without the need for performing the HSQC analysis, we can predict the 13 C dimension by just performing 1 H HRMAS NMR experiment. We show on a rat model of central nervous system tissues (80 samples, 5 tissues) that our methods achieve 0.971 and 0.957 mean R2 values, respectively. Our tests on 15 human brain tumor samples show that we can predict 104 groups of 39 metabolites with 97 percent accuracy. Finally, we show that we can predict the presence of a drug resistant tumor biomarker (creatine) despite obstructed signal in 1 H dimension. In practice, this information can provide valuable feedback to the surgeon to further resect the cavity to avoid potential recurrence. 

### To cite, use the following bibtex entry:
```
@ARTICLE{8730423,
  author={E. O. {Karakaslar} and B. {Coskun} and H. {Outilaft} and I. J. {Namer} and A. E. {Cicek}},
  journal={IEEE/ACM Transactions on Computational Biology and Bioinformatics}, 
  title={Predicting Carbon Spectrum in Heteronuclear Single Quantum Coherence Spectroscopy for Online Feedback During Surgery}, 
  year={2020},
  volume={17},
  number={2},
  pages={719-725},
  doi={10.1109/TCBB.2019.2920646}}
```
