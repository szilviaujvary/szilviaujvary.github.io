---
title: "Estimating optimal PAC-Bayes bounds with Hamiltonian Monte Carlo"
collection: publications
permalink: /publication/pac_hmc
excerpt: 'We improve empirical PAC-Bayes bounds by estimating their optimal value using HMC samples from the Gibbs (generalized) posterior.'
date: 2023-10-31
venue: '1st Mathematics of Modern Machine Learning workshop, NeurIPS'
paperurl: 'https://arxiv.org/pdf/2310.20053v1.pdf'
---
**Szilvia Ujváry**, Gergely Flamich, Vincent Fortuin, José Miguel Hernández Lobato

## Abstract
An important yet underexplored question in the PAC-Bayes literature is how much
tightness we lose by restricting the posterior family to factorized Gaussian distribu-
tions when optimizing a PAC-Bayes bound. We investigate this issue by estimating
data-independent PAC-Bayes bounds using the optimal posteriors, comparing them
to bounds obtained using MFVI. Concretely, we (1) sample from the optimal Gibbs
posterior using Hamiltonian Monte Carlo, (2) estimate its KL divergence from the
prior with thermodynamic integration, and (3) propose three methods to obtain
high-probability bounds under different assumptions. Our experiments on the
MNIST dataset reveal significant tightness gaps, as much as 5-6% in some cases.

[Download paper here](https://arxiv.org/pdf/2310.20053v1.pdf)
