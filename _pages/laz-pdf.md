---
layout: page
title: Partituras Método de solfeo LAZ 1
permalink: /laz-pdf
---
# LAZ 1 PDF

{% assign pdf_files = site.static_files | where: "pdf", true %}
{% for mypdf in pdf_files %}
  * [{{ mypdf.basename }}]({{ mypdf.path }})
{% endfor %}
