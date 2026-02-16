---
title: "Rapid refitting techniques for Bayesian spectral characterization of the gravitational wave background using pulsar timing arrays"
collection: publications
category: manuscripts
permalink: /en/publications/2023-11-13-need-for-speed
excerpt: 'This paper is about faster, approximate methods to accurately characterise a gravitational wave background spectrum with `ceffyl`'
date: 2023-11-13
venue: 'Physical Review D'
paperurl: 'https://journals.aps.org/prd/abstract/10.1103/PhysRevD.108.103019'
bibtexurl: 'http://academicpages.github.io/files/need-for-speed.bib'
citation: 'Lamb, W. G.; Taylor, S. R.; van Haasteren, R. (2023) Phys. Rev. D 108, 103019'
lang: en
translated: true
---
Pulsar timing arrays (PTAs) have recently found evidence for a nanohertz-frequency stochastic gravitational-wave background (SGWB). Constraining its spectral characteristics will reveal its origins. To achieve this, we must understand how data and modeling conditions in each pulsar influence the precision and accuracy of SGWB spectral recovery, typically requiring many Bayesian analyses on real data sets and large-scale simulations that are slow and computationally taxing. To combat this, we have developed several new rapid approaches that operate on intermediate SGWB analysis products. These techniques refit SGWB spectral models to previously computed Bayesian posterior estimates of the timing power spectra. We test our new techniques on simulated PTA data sets and the NANOGrav 12.5-year data set, where in the latter our refit posterior achieves a Hellinger distance -- bounded between 0 for identical distributions and 1 for zero overlap -- from the current full production-level pipeline that is < 0.1. Our techniques are ~ \\(10^2-10^4\\) times faster than the production-level likelihood and scale much more favorably (sub-linearly) as a PTA is expanded with new pulsars or observations. Our techniques also allow us to demonstrate conclusively that SGWB spectral characterization in PTA data sets is driven by the longest-timed pulsars and the best-measured power spectral densities. Indeed, the common-process spectral properties found in the NANOGrav 12.5-year data set are given by analyzing only the ~14 longest-timed pulsars out of the full 45 pulsar array, and we find that the 'shallowing' of the common-process power-law model occurs when gravitational-wave frequencies higher than ~50 nanohertz are included. The implementation of our techniques is openly available as a software suite to allow fast and flexible PTA SGWB spectral characterization and model selection.