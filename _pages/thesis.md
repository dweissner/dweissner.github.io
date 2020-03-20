---
layout: archive
title: "Thesis"
permalink: /thesis/
author_profile: true
---

Thesis PDF
------------------
[Current Draft of Thesis](https://dweissner.github.io/files/Thesis.pdf)


Thesis Documentation
------------------
[Thesis Documentation](https://dweissner.github.io/Thesis/)



![](/images/changelog.jpg)
<img src="/images/changelog.jpg" width="20">


Change Log
-------------
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.thesis reversed %}
  {% include archive-single.html %}
{% endfor %}
