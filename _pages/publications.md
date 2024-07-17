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

**Journals**

* Durante D., Pozza F. and Szabo B. (2023+). **Skewed Bernstein-von Mises theorem and skew-modal approximations.** *Annals of Statistics (forthcoming)*, Winner of the 2023 ASA-SBSS Student Paper Competition ([pdf](https://arxiv.org/abs/2301.03038))
  
* Pozza F., Kenne Pagui E. C. and Salvan A. (2023). **Improved and computationally stable estimation of relative risk regression with one binary exposure.** *Statistical Methods in Medical Research*, 32(6), 1234-1246.

**Papers under reviews**



**Proceedings**

* Kenne Pagui E. C., Pozza, F. and Salvan A. (2021) 
**Improved maximum likelihood estimator in relative risk regression.**
*Book of Short Papers of the Italian Statistical Society*, Pearson ([pdf](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/Docenti/Università/pearson-sis-book-2021-parte-2.pdf)).


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
