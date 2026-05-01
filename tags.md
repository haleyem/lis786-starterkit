---
title: Tags
layout: page
permalink: /tags
---

## Heading 

a list of all of the tags on the website

<div>
    {% for tag in site.tags %}
    <h3><a href="/lis786-starterkit{{tag.permalink}}">{{ tag.title }}</a></h3>
    {% endfor %}
</div>