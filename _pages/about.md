---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% assign papers = site.publications | where_exp: "p", "p.type != 'report'" | sort: "date" | reverse %}
{% assign reports = site.publications | where: "type", "report" | sort: "date" | reverse %}

Hi! I'm a final-year PhD student in the [ML@CL](https://mlatcl.github.io/) group at the University of Cambridge, supervised by [Ferenc Huszár](https://www.cst.cam.ac.uk/people/fh277). I study **language model generalisation and inductive biases**, with a focus on out-of-distribution **compositional generalisation**, **implicit Bayesian inference**, and **how training data shapes model behaviour**.

Alongside my research, I have hands-on industry experience in LLM **pre-training** at [Apple Machine Learning Research](https://machinelearning.apple.com/), hosted by Marco Cuturi, and **post-training** at [Reasonable](https://reasonable.io/), where I led fine-tuning projects in collaboration with NVIDIA. Previously, I did an MPhil in Machine Learning and Machine Intelligence at Cambridge and a BSc in Mathematics at Imperial College London.

[Email](mailto:sru23@cam.ac.uk) / [Google Scholar](https://scholar.google.com/citations?user=LknnfTQAAAAJ&hl=en) / [GitHub](https://github.com/szilviaujvary) / [LinkedIn](https://www.linkedin.com/in/szilviaujvary) / [CV](/files/szilvia_ujvary_cv_oct_2026.pdf)

## Publications

\* equal contribution

<ul class="pubs">
{% for post in papers %}{% include publication-compact.html %}{% endfor %}
</ul>

### Technical reports

<ul class="pubs">
{% for post in reports %}{% include publication-compact.html %}{% endfor %}
</ul>

## Talks

* **LaCy: What Small Language Models Can and Should Learn is Not Just a Question of Loss.** Invited talk, Hungarian Machine Learning Days, 2026
* **LLMs, Implicit Bayesian Inference and Compositional Generalisation.** Invited talk, [NLIP Seminar Series](https://www.talks.cam.ac.uk/talk/index/231436/), University of Cambridge, 2025
* **Position: Understanding LLMs Requires More Than Statistical Generalization.** Invited talk, Hungarian Machine Learning Days, 2023

## Experience

* **Reasonable**, Budapest — Student Researcher, LLM post-training (2026). Led post-training in two NVIDIA Nemotron early-access projects, fine-tuning 30B–120B parameter models to write formally verified Rust proofs.
* **Apple Machine Learning Research**, Paris — Research Scientist Intern, hosted by Marco Cuturi (2025–2026). Pre-training data selection to reduce hallucinations in small language models.
* **Lakestar**, London — Deep Tech Fellow, part-time (2024)
* **University of Cambridge** — Research Assistant with Ferenc Huszár (2022)

## Education

* **University of Cambridge** — PhD in Machine Learning (2023–2027, expected). Visiting student in the Computational and Biological Learning Lab with José Miguel Hernández-Lobato.
* **University of Cambridge** — MPhil in Machine Learning and Machine Intelligence (2022–2023). Distinction, ranked 2nd of 44, best dissertation in cohort.
* **Imperial College London** — BSc in Mathematics (2019–2022). First Class Honours, Dean's List in all three years.

## Awards & service

* Citadel PhD Summit 2026: Third Prize and a £4,000 research grant
* ICML 2026 Silver Reviewer award; reviewer for ICML, NeurIPS, ICLR
* Emmanuel College, Cambridge: full MPhil scholarship (2022)
* G-Research Prize, Imperial College London (2021)
* Marjorie McDermott Scholarship, Imperial College London (2020–2022)
