---
title: Political and Philosophical Perspectives
layout: page
permalink: /ideologies
nav-include: true
---

TEXT

## Heading

{% for ideology in site.ideologies %}
<div class="box">
<div class="content-left">
<h3><a href="/lis786-starterkit{{ideology.permalink}}">{{ ideology.title }}</a></h3>
<p>{{ ideology.snip }}</p>
<p>{{ ideology.content }}</p>
</div>
{% if ideology.image != blank %}
{% continue %}
<div class="img-right">
    <figure class="img-inner">
    <img src="{{ ideology.image }}">
    </figure>
</div>
{% endif %}
</div>
{% endfor %}
