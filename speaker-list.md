---
layout: page
title: Speaker List
permalink: /speaker-list/
---
{% for a in site.data.authors %}{% if a.speaker == 'True' %}
{% assign author = a %}
{% include author.html %}
{% endif %}{% endfor %}