---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
---

<iframe src="https://dweissner.github.io/files/Resume_WeissnerDeborah.pdf" width="100%" height="800px" style="border: none;"></iframe>

<a href="https://dweissner.github.io/files/Resume_WeissnerDeborah.pdf" target="_blank">Download PDF</a>
{% include base_path %}

{% for post in site.thesis reversed %}
  {% include archive-single.html %}
{% endfor %}
