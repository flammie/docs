---
layout: base
title:  'Dependencies'
generated: 'true'
permalink: Urj/dep/index.html
---

# Dependencies

{% include Urj-dep-table.html %}

----------

Alphabetical listing

{% assign sorted = site.Urj-dep | sort: 'title' %}{% for p in sorted %}
* [{{ p.title }}](): {{ p.shortdef }}{% endfor %}
