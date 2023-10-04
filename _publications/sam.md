---
title: "Rethinking Sharpness-Aware Minimization as Variational Inference"
collection: publications
permalink: /publication/sam
excerpt: 'We connect the Sharpness-Aware Minimization (SAM) algorithm to mean-field variational inference and derive novel optimization algorithms building on the said connection.'
venue: '14th International OPT Workshop on Optimization for Machine
Learning, NeurIPS 2022'
paperurl: 'https://opt-ml.org/papers/2022/paper102.pdf'
---
Sharpness-aware minimisation (SAM) aims to improve the generalisation of gradient-based learn-
ing by seeking out flat minima. In this work, we establish connections between SAM and mean-
field variational inference (MFVI) of neural network parameters. We show that both these methods
have interpretations as optimizing notions of flatness, and when using the reparametrisation trick,
they both boil down to calculating the gradient at a perturbed version of the current mean param-
eter. This thinking motivates our study of algorithms that combine or interpolate between SAM
and MFVI. We evaluate the proposed variational algorithms on several benchmark datasets, and
compare their performance to variants of SAM. Taking a broader perspective, our work suggests
that SAM-like updates can be used as a drop-in replacement for the reparametrisation trick.

[Download paper here](https://opt-ml.org/papers/2022/paper102.pdf)
