---
layout: archive
title: "Research"
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

Kwong-Yu Wong. (2021). &quot;[Dynamic Competition of Real Estate Developers in Hong Kong: Lesson on Counter-cycle Policy](http://academicpages.github.io/files/paper1.pdf)&quot; <i>Working Paper</i>. 1(1).
