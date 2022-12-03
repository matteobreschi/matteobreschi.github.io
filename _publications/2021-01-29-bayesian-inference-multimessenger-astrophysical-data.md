---
title: "`bajes`: Bayesian inference of multimessenger astrophysical data, methods and application to gravitational-waves"
collection: publications
permalink: /publication/2021-01-29-bayesian-inference-multimessenger-astrophysical-data
authors: 'Matteo Breschi, Rossella Gamba, Sebastiano Bernuzzi'
date: 2021-01-29
venue: 'Phys.Rev.D 104 (2021) 4, 042001'
paperurl: 'https://doi.org/10.1103/PhysRevD.104.042001'
arxivnumber: '2102.00017'
arxivclass: '[gr-qc]'
---

We present `bajes`, a parallel and lightweight framework for Bayesian inference of multimessenger transients. `bajes` is a Python modular package with minimal dependencies on external libraries adaptable to the majority of the Bayesian models and to various sampling methods. We describe the general workflow and the parameter estimation pipeline for compact-binary-coalescence gravitational-wave transients. The latter is validated against injections of binary black hole and binary neutron star waveforms, including confidence interval tests that demonstrates the inference is well-calibrated. Binary neutron star postmerger injections are also studied using a network of five detectors made of LIGO, Virgo, KAGRA and Einstein Telescope. Postmerger signals will be detectable for sources at ≲80Mpc, with Einstein Telescope contributing over 90\% of the total signal-to-noise ratio. As a full scale application, we re-analyze the GWTC-1 black hole transients using the effective-one-body TEOBResumS approximant, and reproduce selected results with other approximants. `bajes` inferences are consistent with previous results; the direct comparison of `bajes` and `bilby` analyses of GW150914 shows a maximum Jensen-Shannon divergence of 5.2×10−4. GW170817 is re-analyzed using TaylorF2 with 5.5PN point-mass and 7.5PN tides, TEOBResumSPA, and IMRPhenomPv2_NRTidal with different cutoff-frequencies of 1024Hz and 2048Hz. We find that the former choice minimizes systematics on the reduced tidal parameter, while a larger amount of tidal information is gained with the latter choice. `bajes` can perform these analyses in about 1~day using 128 CPUs.

Download the code on [GitHub](https://github.com/matteobreschi/bajes)

Posterior samples of the EOB catalog are released on [Zenodo](https://doi.org/10.5281/zenodo.4476594)

![Figure](/images/publications/2021-01-29-bayesian-inference-multimessenger-astrophysical-data.png)
