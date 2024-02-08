---
title: IAccessible's Include series
permalink : /events
---
We are excited to announce the launch of IAccessible's "Include" series. This series is designed to bring together thought leaders, industry experts, and accessibility enthusiasts to discuss the latest trends, challenges, and opportunities in the accessibility space.


{% for post in site.posts %}
    {% if post.categories contains "event-include" %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
    {% endif %}
{% endfor %}

