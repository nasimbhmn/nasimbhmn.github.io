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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- * **Bahmanian, N.**, & Eslami, M. Early peak: a case in Persian. In _Proc. TAL2018, Sixth International Symposium on Tonal Aspects of Languages_ (pp. 140-144).

* **Bahmanian, N.**, & Eslami, M. pishnahâd-e chârchubi barâye tahiyye-ye farhang-hâ-ye zabân âmuz-e Fârsi [A theoretical and practical framework in developing Persian learners’ dictionaries]. In _Proceeding of the second Allame Dehkhoda conference on Persian lexicography_, February 2016, Dehkhoda Lexicon Institute, Tehran. -->

