---
title: Political and Philosophical Perspectives
layout: page
permalink: /ideology
nav-include: true
---

TEXT

## Heading

{% for ideology in site.ideologies %}
<div class="box">
<div class="content-left">
<h3>{{ ideology.title }}</h3>
<p>{{ ideology.snip }}</p>
<p>{{ ideology.content }}</p>
</div>
{% if ideology.image != blank %}
<div class="img-right">
    <figure class="img-inner">
    <img src="{{ ideology.image }}">
    </figure>
</div>
{% endif %}
</div>
{% endfor %}
