---
layout: page
title: Partituras Método de solfeo LAZ 1
permalink: /laz-midi
---
# LAZ 1 midi

{% assign midi_files = site.static_files | where: "midi", true %}
{% for mymidi in midi_files %}
  * [{{ mymidi.basename }}]({{ mymidi.path }})
{% endfor %}
