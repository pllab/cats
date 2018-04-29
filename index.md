---
layout: page
permalink: /
---

This is the webpage for category theory reading group at [UCSB PL Lab](https://cs.ucsb.edu/~pllab). During Spring '18 quarter, we are meeting on Thursdays 2-3pm at Phelps 3518 and we will follow <!-- [Category Theory for Computing Science](This is the webpage for category theory study group at UCSB PL Lab) by Michael Barr and Charles Wells. -->
[Seven Sketches in Compositionality: An Invitation to Applied Category Theory](https://arxiv.org/abs/1803.05316) by Brendan Fong and David I Spivak.

# Past and upcoming topics

{% for post in site.posts %}
 * <span>{{ post.present-date | date: "%b %-d, %Y" }}</span> - <a href="{{ post.url | prepend: site.baseurl }}" title="{{ post.title }}">{{ post.title }}</a>
{% endfor %}
