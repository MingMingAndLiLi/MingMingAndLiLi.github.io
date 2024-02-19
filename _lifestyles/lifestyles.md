---
layout: single
title: "日常"
permalink: /lifestyles/
author_profile: true
---

{% include base_path %}

<!-- {% for post in site.lifestyless reversed %}
  {% include lifestyles-row.html %}
{% endfor %} -->

{% if site.lifestyles %}
  {% assign lifestyles = site.lifestyles%}
  {% include lifestyle-row.html %}
{% endif%}