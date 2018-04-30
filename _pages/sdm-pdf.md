---
layout: page
title: Partituras sociedad didáctico musical 1
permalink: /sdm-pdf
---
# SDM(Sociedad didáctico musical) 1 pdf

{% assign pdf_files = site.static_files | where: "pdf", true %}
{% for mypdf in pdf_files %}
  * [{{ mypdf.basename }}]({{ mypdf.path }})
{% endfor %}
