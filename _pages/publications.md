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

# Job Market Paper
Kwong-Yu Wong. (2021). &quot;[Dynamic Competition of Real Estate Developers in Hong Kong: Lesson on Counter-cycle Policy](http://academicpages.github.io/files/paper1.pdf)&quot; <i>Working Paper</i>. 1(1).

# Work in progress
Thor Morris & Kwong-Yu Wong. (2021) &quot;[Reddit, Retail Investor and Music Chair in Finance]()&quot; 

Zhihao Chen, Minyan Shen & Kwong-Yu Wong (2020) &quot;[Productivity Measurement, Deep Learning and Scanner Data]()&quot; 

Wenzheng Mao & Kwong-Yu Wong (2019) &quot;[Productive Competition under Rationing: Evidence from Food Delivery in China]()&quot; 
