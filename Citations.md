---
title: Citations
layout: page
permalink: /citations
---
# Citations and Formatting 

Here's where you'll find resources to help you with formatting and citations in: 

- MLA 
- APA 
- Chicago 

You can also learn basic formatting tips by watching quick videos like this one: 

{% include video.html youtube_id="qcY2RVVJHGU" yt_title="How to Create a Hanging Indent" %}

{% for resource in site.resources %}
{% if resource.category == 'formatting' %}
<h3>{{ resource.title }}</h3>
<p><img src="{{ resource.image }}" alt="{{ resource.alt }}"/></p>
<p>{{ resource.content }}</p>
<p>Category: {{ resource.category }}</p>
{% endif %}
{% endfor %}
