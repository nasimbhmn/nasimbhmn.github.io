---
layout: archive
title: ""
permalink: /presentations/
author_profile: true
---


Peer-reviewed poster presentations
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.presentations reversed %}
  {% include archive-single.html %}
{% endfor %}