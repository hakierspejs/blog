---
title: Home
layout: default
---

1. [Recent](#recent)
2. [More](#more)
3. [Contributing](#contributing)
4. [About](#about)

## <a name="recent"></a>Recent

Latest posts written by members of our hackerspace and friends. Best place to spread your project ideas.

{% for post in site.posts limit: 3 %}

### {{ post.title }}

_Written by [@{{ post.author }}]({{ post.website }}), {{ post.date | date_to_string }}._

{{ post.excerpt }}

_[Read it...]({{post.url}})_

{% endfor %}

## <a name="more"></a>More

You can find even more content [here](/posts).

## <a name="contributing"></a>Contributing

Want to contribute to this blog? Don't hesitate! Open pull request [here](https://github.com/hakierspejs/blog) with your post content or send it to [@thinkofher](https://beniamindudek.xyz/contact) or our [mailing list](mailto:lodz@lists.hackerspace.pl).

## <a name="about"></a>About

We're a group of people passionate about open source, DYI and free culture movement. We organize meetings, share knowledge and do fun projects. Check our [homepage](https://lodz.hackerspace.pl/) and [wiki](https://github.com/hakierspejs/wiki/wiki) for more information.
