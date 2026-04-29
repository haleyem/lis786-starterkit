---
title: Content by Topic
layout: page
permalink: /by_topic
nav-include: true
---
<div>
  Search through all of my posts by topic!
</div>

<div>
    {% for post_tags in site.tag %}
    <h3>{{ tag.title }}</h3>
    <p><img src="{{tag.image}}"></p>
    <p>{{ tag.content }}</p>
    {% endfor %}
</div>

{{ site.tags }}
