---
title: Tags
layout: page
permalink: /tags
nav-include: true
---

## Heading 

a list of all of the tags on the website

this html was working at least

<ul>
  {% for tag in site.tags %}
    <li>{{ tag | first }}</li>
  {% endfor %}
</ul>

<div>
    {% for tag in site.tags %}
    <h3><a href="/lis786-starterkit{{tag.permalink}}">{{ tag.title }}</a></h3>
    <p>{{ tag.snip }}</p>
    <p><img src="{{tag.image}}"></p>
    {% endfor %}
</div>
