---
title: Posts
layout: default
---

## Posts

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) by [@{{ post.author }}]({{ post.website }}), {{ post.date | date_to_string }}
{% endfor %}

---

Show me [tags](/tags) or take me back to the [home](/).
