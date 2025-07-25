---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



## Current projects

* **Unified Inference framework for functionals: Assumption-flexible with Post-Selection Guarantees**
  * Developing methods for deriving confidence intervals for various functionals (e.g., mean or median) under user-specified assumptions (e.g., finite variance or tail behavior), using confidence sets for CDFs.
  * This offers a flexible inference strategy that reduces dependence on strict assumptions and enhances applicability across diverse contexts.

* **Inference for quantile-parametrized distributions**
  * Quantile-based distributions are flexible and widely applicable, but lack closed-form densities, making standard inference challenging.
  * Classical methods like MLE can yield non-$\sqrt{n}$ and non-normal asymptotic behavior in certain parameter regions, making bootstrap and resampling techniques unreliable.
  * We develop a new inference framework tailored to parametric models defined via the quantile function, offering principled and assumption-lean alternatives for inference.

* **Random forests and decision trees**
  * Focusing on density estimation trees (DETs), a data-driven partitioning approach for tree-structured density estimation.
  * Establishing the necessary conditions for DETs to be consistent estimators, under different metrics such as $$L^2$$ norm or KL divergence.
  * Exploring methods to quantify uncertainty in density estimates from DETs, enhancing their reliability and interpretability in machine learning applications.


## Submitted papers and pre-prints
* **New Asymptotic Limit Theory and Inference for Monotone
Regression**<br />
Soham Mallick, Siddhaarth Sarkar, Arun Kuchibhotla (2023) <br />
 [arXiv](https://arxiv.org/pdf/2310.20058)

* **Post-selection Inference for Conformal Prediction: Trading off Coverage for Precision**<br /> Siddhaarth Sarkar, Arun Kumar Kuchibhotla (2023)<br />
[arXiv](https://arxiv.org/abs/2304.06158) 



