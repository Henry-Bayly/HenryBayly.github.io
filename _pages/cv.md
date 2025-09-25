---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Biostatistics, Boston University, 2027 (expected)
* B.A. in Mathematics, Boston College, 2022

Dissertation
======
* May 2025 - Present (Advisor: Prasad Pratil)
  * Advancing Ensemble Methods: I am interested in model generalization for ensemble learning methods with multi-site data with applications in targeted gene discovery.

Research experience
======
* June 2022 - Present: Graduate Research Assistant (Research Advisors: Mark Logue and Yorghos Tripodis)
  * Conducted epigenome-wide survival analysis of DNA methylation in relation to Alzheimer’s disease onset using approximately 750,000 Cox proportional hazards models
  * Designed a machine learning pipeline with multimodal clinical and cognitive data to optimize Alzheimer’s disease clinical trial enrollment, boosting trial statistical power by as much as 50%, while enhancing interpretability and equity in patient selection.
  * Built a causal mediation framework linking SNPs, methylation, and PTSD severity using counterfactual modeling
  * Conducted the largest Alzheimer’s GWAS meta-analysis to date, identifying novel loci through integration of multi-cohort summary statistics

* February 2021 - May 2022: Undergraduate Research Assistant
  * Conducted research on probabilistic models for predicting structural changes in social networks
  * Contributed to a publication presenting a streamlined proof of existence and uniqueness of maximum likelihood estimates (MLEs) in exponential random graph models (ERGMs)
  * Supervisor: Kathryn Lindsey
  
Skills
======
* Programming: R (tidyverse, dplyr, caret), Python (scikit-learn, pandas, PyTorch), SAS, Bash, SQL
* Machine Learning: Supervised/unsupervised learning, ensemble methods, neural networks
* Statistical Modeling: GLMs, mixed-effects models, survival analysis, causal inference

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
