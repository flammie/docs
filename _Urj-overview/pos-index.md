---
layout: base
title:  'POS tags'
generated: 'true'
permalink: Urj/pos/index.html
---

# POS tags

{% include Urj-pos-table.html %}

----------

Alphabetical listing

{% assign sorted = site.Urj-pos | sort: 'title' %}{% for p in sorted %}
* [{{ p.title }}](): {{ p.shortdef }}{% endfor %}
