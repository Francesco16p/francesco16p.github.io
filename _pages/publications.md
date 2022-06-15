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


**Proceedings**

* Kenne Pagui E. C., Pozza, F. and Salvan A. (2021) 
**Improved maximum likelihood estimator in relative risk regression.**
*Book of Short Papers of the Italian Statistical Society*, Pearson ([pdf](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/Docenti/Università/pearson-sis-book-2021-parte-2.pdf)).


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
