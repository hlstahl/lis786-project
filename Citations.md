---
title: Citations
layout: page
permalink: /citations
---
# Citations and Formatting 

{% for resource in site.resources %}
    {% if resource.category == 'formatting' %}
        <br>
        <hr>
        <h3>{{ resource.title }}</h3>
        <p><img class="listing" src="{{ resource.image }}" alt="{{ resource.alt }}"/></p>
        <p class="listing">{{ resource.excerpt }}</p>
        <p>Category: {{ resource.category }}</p>
    {% endif %}
{% endfor %}
