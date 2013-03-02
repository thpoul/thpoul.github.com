---
layout: default
---
{% include JB/setup %}


<h2>Working on it :)</h2>
<div class="blog-index">
	{% for post in site.posts %}
		<h2 class="entry-title">
			<a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
			<small>{{ post.date | date_to_string }}</small>
		</h2>
		<p>{{ post.content }}</p>
	{% endfor %}
</div>


