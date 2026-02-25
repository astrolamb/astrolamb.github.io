---
title: "Deep Neural Emulation of the Supermassive Black Hole Binary Population"
pubtype: short-author
collection: publications
tags: short-author
category: manuscripts
permalink: /en/publications/2025-03-19-deep-neural
excerpt:
date: 2025-03-19
venue: 'ApJ'
paperurl: 'https://iopscience.iop.org/article/10.3847/1538-4357/adb4ef/meta'
#bibtexurl:
citation: 'Nima Laal et al 2025 ApJ 982 55'
lang: en
translated: false
---

While supermassive black hole (SMBH) binaries are not the only viable source for the low-frequency gravitational wave background (GWB) signal evidenced by the most recent pulsar timing array (PTA) data sets, they are expected to be the most likely. Thus, connecting the measured PTA GWB spectrum and the underlying physics governing the demographics and dynamics of SMBH binaries is extremely important. Previously, Gaussian processes (GPs) and dense neural networks have been used to make such a connection by being built as conditional emulators; their input is some selected evolution or environmental SMBH binary parameters and their output is the emulated mean and standard deviation of the GWB strain ensemble distribution over many Universes. In this paper, we use a normalizing flow (NF) emulator that is trained on the entirety of the GWB strain ensemble distribution, rather than only mean and standard deviation. As a result, we can predict strain distributions that mirror underlying simulations very closely while also capturing frequency covariances in the strain distributions as well as statistical complexities such as tails, non-Gaussianities, and multimodalities that are otherwise not learnable by existing techniques. In particular, we feature various comparisons between the NF-based emulator and the GP approach used extensively in past efforts. Our analyses conclude that the NF-based emulator not only outperforms GPs in the ease and computational cost of training but also outperforms in the fidelity of the emulated GWB strain ensemble distributions.

**My Contributions**
Software development of [`holodeck`](https://github.com/nanograv/holodeck).