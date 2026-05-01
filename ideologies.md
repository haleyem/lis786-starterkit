---
title: Political and Philosophical Perspectives
layout: page
permalink: /ideologies
nav-include: true
---

There are various branches of feminism, all with different grounding philosophies. In the last 100 years, the three most influential have been liberal feminism, Marxist feminism, and radical feminism. 

## Feminist Ideologies

{% for ideology in site.ideologies %}
<div>
<div class="content-left">
<h3><a href="/lis786-starterkit/{{ideology.permalink}}">{{ ideology.title }}</a></h3>
<p>{{ ideology.snip }}</p>
<p>{{ ideology.content }}</p>
</div>
{% if ideology.image %}
{% unless ideology.image == blank %}
<div class="img-right" class="ideo">
    <figure class="img-inner">
    <img src="{{ ideology.image }}">
    </figure>
</div>
{% endunless %}
{% endif %}
</div>
{% endfor %}
