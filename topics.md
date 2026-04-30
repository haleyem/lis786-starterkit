---
title: Content by Topic
layout: page
permalink: /content_by_topics
nav-include: true
---

## Search through all of my posts by topic!

<div class="content-left">
    {% for tagged in site.topics %}
    <h3><a href="/lis786-starterkit{{tagged.permalink}}">{{ tagged.title }}</a></h3>
    <p>{{ tagged.snip }}</p>
</div>
<div class="img-right">
    <p><img src="{{tagged.image}}"></p>
</div>
    {% endfor %}


8:33 run
