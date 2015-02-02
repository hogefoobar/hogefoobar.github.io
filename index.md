---
title: hogefoobar.github.io
layout: defalut
---

# hogefoobar.github.io
Here is my page.

<ul>
	{% for post in site.posts %}
	<li>
		<a href="{{ post.url }}">{{ post.title }}</a>
		{{ post.excerpt }}
	</li>
	{% endfor %}
</ul>
