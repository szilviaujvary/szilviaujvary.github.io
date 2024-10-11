---
title: "Position Paper: Understanding LLMs Requires More than Statistical Generalization"
collection: publications
permalink: /publication/position
excerpt: 'We illustrate how statistical generalisation does not explain the emergent abilities of today's AR probabilistic models, and propose relevant research directions in OOD-generalisation and inductive biases.'
date: 2023-06-17
venue: 'Spotlight, International Conference on Machine Learning (ICML)'
paperurl: 'https://arxiv.org/pdf/2405.01964.pdf'
---
Patrik Reizinger*, **Szilvia Ujváry***, Anna Mészáros*, Anna Kerekes*, Wieland Brendel, Ferenc Huszár

## Abstract
The last decade has seen blossoming research in deep learning theory attempting to answer,“Why does deep learning generalize?" A powerful shift in perspective precipitated this progress: the study of overparametrized models in the interpolation regime. In this paper,we argue that another perspective shift is due, since some of the desirable qualities of LLMs are not a consequence of good statistical generalization and require a separate theoretical explanation. Our core argument relies on the observation that AR probabilistic models are inherently non-identifiable: models zero or near-zero KL divergence apart—thus, equivalent test loss—can exhibit markedly different behaviors. We support our position with mathematical examples and empirical observations, illustrating why non-identifiability has practical relevance through three case studies: (1) the non-identifiability of zero-shot rule extrapolation; (2) the approximate non-identifiability of in-context learning; and (3)the non-identifiability of fine-tunability. We review promising research directions focusing on LLM-relevant generalization measures, transferability, and inductive biases.

[Download paper here](https://arxiv.org/pdf/2405.01964)
