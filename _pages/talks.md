---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% include base_path %}

**Contributed talks**

* [SIS2021](https://meetings3.sis-statistica.org/index.php/sis2021/) 50th Meeting of the Italian Statistical Society, virtual (June 21-25, 2021).

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
