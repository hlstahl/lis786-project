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

You can also learn basic formatting tips like this one: 

{% include video.html youtube_id="qcY2RVVJHGU" yt_title="How to Create a Hanging Indent" %}

{% for resource in site.resources %}
{% if resource.category == 'formatting' %}
<h3>{{ resource.title }}</h3>
<p><img src="{{ resource.image }}" alt="Basics of MLA include one inch margins, 
Times New Roman font size 12, double spacing, last name and page number in top right, and indeting 
the first line of each paragraph 1/2 inch."/></p>
<p>{{ resource.content }}</p>
<p>Category: {{ resource.category }}</p>
{% endif %}
{% endfor %}
