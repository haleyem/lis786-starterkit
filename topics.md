---
title: Content by Topic
layout: page
permalink: /content_by_topics
nav-include: true
---

## Search through all of my posts by topic!

<div markdown="1">
    {% for tagged in site.topics %}
    <h3><a href="/lis786-starterkit{{tagged.permalink}}">{{ tagged.title }}</a></h3>
    <p><img src="{{tagged.image}}"></p>
    <p>{{ tagged.content }}</p>
    {% endfor %}
</div>


6:15 run
