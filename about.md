layout: page
title: "about me"
permalink: /about

<ul>
{% for post in site.posts %}
	<li>
	<a href="{{ post.url }}">{{ post.title }}</a>
	</li>
{% endfor %}
</ul>
