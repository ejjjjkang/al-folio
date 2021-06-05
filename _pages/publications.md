---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
field: [Paper, Short paper and Workshop, Others]
nav: true
---

<div class="publications">

{% for y in page.field %}

  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[field={{y}}]* %}
{% endfor %}

</div>
