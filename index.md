---
layout: default
---
# Presentations
{% for post in site.posts %}
## <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
