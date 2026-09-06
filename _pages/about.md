---
permalink: /
title: 
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a **Research Economist** at the **Bank of England**. Previously I was Post-doctoral Research Fellow at Bocconi University. 

My research interests are in empirical macroeconomics and econometrics.


## Research

{% assign sorted_publications = site.publications | sort: "date" | reverse %}
{% for post in sorted_publications %}
  {% include archive-single.html %}
{% endfor %}

## Curriculum Vitae

[Download my CV](https://drive.google.com/file/d/1_qBGg3A8s-hcHU6tgAynG2jlOqJmvtTq/view?usp=drive_link){: .btn .btn--primary }

