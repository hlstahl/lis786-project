---
title: Citations
layout: page
permalink: /citations
---
# Citations and Formatting 

{% for resource in site.resources %}
{% if resource.category == 'formatting' %}
<h3>{{ resource.title }}</h3>
<p><img src="{{ resource.image }}" alt="{{ resource.alt }}"/></p>
<p>{{ resource.content }}</p>
<p>Category: {{ resource.category }}</p>
{% endif %}
{% endfor %}
