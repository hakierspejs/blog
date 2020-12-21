---
title: Home
layout: default
---

## Tags

Posts separated by tags.

{% for tag in site.tags %}
- <a name="{{ tag[0] }}"></a>{{ tag[0] }}
    {% for post in tag[1] %}
    - [{{ post.title }}]({{ post.url }})
    {% endfor %}
{% endfor %}

---

Show me all [posts](/posts) or take me back to the [home](/).
