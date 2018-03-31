---
layout: page
title: Ficheros
permalink: /solfeo-laz
---
# LAZ 1 PDF

Ficheros pdf correspondientes libro primero del método LAZ de solfeo

{% assign pdf_files = site.static_files | where: "pdf", true %}
{% for mypdf in pdf_files %}
  * [{{ mypdf.basename }}]({{ mypdf.path }})
{% endfor %}

# LAZ 1 midi

{% assign midi_files = site.static_files | where: "midi", true %}
{% for mymidi in midi_files %}
  * [{{ mymidi.basename }}]({{ mymidi.path }})
{% endfor %}
