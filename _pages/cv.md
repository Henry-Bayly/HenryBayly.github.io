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
  * My dissertation focuses on adapting Machine Learning prediction methods to clinical and epidemiological study settings.
  * I am tackling questions of interpretability, complex study designs, and small sample size prediction.
  
Research experience
======
* June 2022 - Present: Graduate Research Assistant (Research Advisors: Mark Logue and Yorghos Tripodis)
  * My research broadly focuses on neurological disorders, with an emphasis on disentangling the genetic architecture underlying different diseases and understanding how they are related.
  * I am also interested in the use of prediction models to better inform sample selection in clinical trials, particularly for Alzheimer's Disease.

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
  
