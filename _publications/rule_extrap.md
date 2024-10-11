---
title: "Rule Extrapolation in Language Models: A Study of Compositional Generalization on OOD Prompts"
collection: publications
permalink: /publication/rule_extrap
excerpt: 'We introduce rule extrapolation, a novel metric of OOD compositional generalisation on formal languages, and evaluate it on several AR Language model architectures. We also propose a normative model to explain OOD behaviour via simplicity bias.'
date: 2024-09-09
venue: 'Spotlight, Neural Information Processing Systems'
paperurl: 'https://arxiv.org/pdf/2409.13728.pdf'
---
Anna Mészáros, **Szilvia Ujváry**, Wieland Brendel Patrik Reizinger*, and
Ferenc Huszár*

## Abstract
LLMs show remarkable emergent abilities, such as inferring concepts from presumably out-of-distribution prompts, known as in-context learning. Though this success is often attributed to the Transformer architecture, our systematic understanding is limited. In complex real-world data sets, even defining what is out-of-distribution is not obvious. To better understand the OOD behaviour of autoregressive LLMs, we focus on formal languages, which are defined by the intersection of rules. We define a new scenario of OOD compositional generalization, termed rule extrapolation. Rule extrapolation describes OOD scenarios, where the prompt violates at least one rule. We evaluate rule extrapolation in formal languages with varying complexity in linear and recurrent architectures, the Transformer, and state space models to understand the architectures’ influence on rule extrapolation. We also lay the first stones of a normative theory of rule extrapolation, inspired by the Solomonoff prior in algorithmic information theory.

[Download paper here](https://arxiv.org/pdf/2409.13728.pdf)
