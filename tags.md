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
    <p>{{ tag.snip }}</p>
    <p><img src="{{tag.image}}"></p>
    {% endfor %}
</div>

    {% for post in site.posts %}
    {% assign tags = tags | concat:post.tags %}
    {% endfor %}
    {% assign tags = tags | uniq | sort %}