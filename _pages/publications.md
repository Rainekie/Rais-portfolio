---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
description: Journal articles, conference proceedings, and patents by Rai Sato.
---

<p class="publication-counts"><strong>{% bibliography_count -f papers -q @*[keywords=journal] %}</strong> journal articles <span>·</span> <strong>{% bibliography_count -f papers -q @inproceedings %}</strong> conference papers <span>·</span> <strong>{% bibliography_count -f papers -q @*[keywords=patent] %}</strong> granted patent</p>

<div class="publications publication-list">
  {% bibliography %}
</div>
