---
title: Content by Topic
layout: page
permalink: /topics
nav-include: true
---

## Search through all of my posts by topic!

<div>
    {% for tagged in site.topics %}
    <h3><a href="/{{tagged.permalink}}">{{ tagged.title }}</a></h3>
    <p><img src="{{tagged.image}}"></p>
    <p>{{ tagged.content }}</p>
    {% endfor %}
</div>

5:25 run
