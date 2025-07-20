---
layout: archive
title: "Life & Travel"
permalink: /lifeandtravel/
author_profile: true
---

{% include base_path %}

{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% if post.tags contains "lifeandtravel" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %} 