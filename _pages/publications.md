---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

### Publication

{% include base_path %}
{% for post in site.publications reversed %}
  {% if post.categories contains 'pub' %}
  {% include archive-single.html %}
    {% endif %}
{% endfor %}

<hr class="new1">

### Working Papers

{% include base_path %}
{% for post in site.publications reversed %}
  {% if post.categories contains 'wp' %}
  {% include archive-single.html %}
    {% endif %}
{% endfor %}

<hr class="new1">

### Work in Progress

{% include base_path %}
{% for post in site.publications reversed %}
  {% if post.categories contains 'ip' %}
  {% include archive-single.html %}
    {% endif %}
{% endfor %}

<hr class="new1">
