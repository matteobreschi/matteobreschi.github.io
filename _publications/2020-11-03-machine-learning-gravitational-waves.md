---
title: "Machine Learning Gravitational Waves from Binary Black Hole Mergers"
collection: publications
permalink: /publication/2020-11-03-machine-learning-gravitational-waves
authors: 'Stefano Schmidt, Matteo Breschi, Rossella Gamba, Giulia Pagano, Piero Rettegno, Gunnar Riemenschneider, Sebastiano Bernuzzi, Alessandro Nagar, Walter Del Pozzo'
date: 2020-11-03
venue: 'Phys.Rev.D 103 (2021) 4, 043020'
paperurl: 'https://doi.org/10.1103/PhysRevD.103.043020'
arxivnumber: '2011.01958'
arxivclass: '[gr-qc]'
---

We apply machine learning methods to build a time-domain model for gravitational waveforms from binary black hole mergers, called mlgw. The dimensionality of the problem is handled by representing the waveform's amplitude and phase using a principal component analysis. We train mlgw on about O(1e3) TEOBResumS and SEOBNRv4 effective-one-body waveforms with mass ratios q∈[1,20] and aligned dimensionless spins s∈[−0.80,0.95]. The resulting models are faithful to the training sets at the ∼1e−3 level (averaged on the parameter space). The speed up for a single waveform generation is a factor 10 to 50 (depending on the binary mass and initial frequency) for TEOBResumS and approximately an order of magnitude more for SEOBNRv4. Furthermore, mlgw provides a closed form expression for the waveform and its gradient with respect to the orbital parameters; such an information might be useful for future improvements in GW data analysis. As demonstration of the capabilities of mlgw to perform a full parameter estimation, we re-analyze the public data from the first GW transient catalog (GWTC-1). We find broadly consistent results with previous analyses at a fraction of the cost, although the analysis with spin aligned waveforms gives systematic larger values of the effective spins with respect to previous analyses with precessing waveforms. Since the generation time does not depend on the length of the signal, our model is particularly suitable for the analysis of the long signals that are expected to be detected by third-generation detectors. Future applications include the analysis of waveform systematics and model selection in parameter estimation.
