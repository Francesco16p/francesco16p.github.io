---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
**Submitted**

* Pozza F., Zanella G. (2024+). **On the fundamental limitations of multiproposal Markov chain Monte Carlo algorithms.** *Submitted*([pdf](https://arxiv.org/pdf/2410.23174))
  
* Pozza F., Durante D. and Szabo B. (2024+). **Skew-symmetric approximations of posterior distributions.** *Submitted*([pdf](https://arxiv.org/abs/2409.14167))

**Journals**

* Durante D., Pozza F. and Szabo B. (2024). **Skewed Bernstein-von Mises theorem and skew-modal approximations.** *The Annals of Statistics 52 (6), 2714-2737*, Winner of the 2024 ASA-SBSS Laplace Award ([pdf](https://arxiv.org/abs/2301.03038))
  
* Pozza F., Kenne Pagui E. C. and Salvan A. (2023). **Improved and computationally stable estimation of relative risk regression with one binary exposure.** *Statistical Methods in Medical Research*, 32(6), 1234-1246.

**Proceedings**

* Pozza, F. (2024) 
**An application of skew-symmetric approximations of posterior distributions to logistic regression.**
*Book of Short Papers of the Italian Statistical Society*.

* Kenne Pagui E. C., Pozza, F. and Salvan A. (2021) 
**Improved maximum likelihood estimator in relative risk regression.**
*Book of Short Papers of the Italian Statistical Society*, Pearson ([pdf](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/Docenti/Università/pearson-sis-book-2021-parte-2.pdf)).


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
