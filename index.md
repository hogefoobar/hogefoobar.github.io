---
title: hogefoobar.github.io
layout: post
---

# hogefoobar.github.io
This is blog.


<ul>
	{% for post in site.posts %}
	<li>
		<a href="{{ post.url }}">{{ post.title }}</a>
	</li>
	{% endfor %}
</ul>
