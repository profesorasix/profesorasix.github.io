---
layout: page
title: Partituras sociedad didáctico musical 1 
permalink: /sdm-midi
---
# SDM(Sociedad didáctico musical) 1 midi

{% assign midi_files = site.static_files | where: "midi", true %}
{% for mymidi in midi_files %}
  * [{{ mymidi.basename }}]({{ mymidi.path }})
{% endfor %}
