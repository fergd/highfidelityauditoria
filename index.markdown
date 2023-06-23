---
layout: home
---
{% for post in site.posts %}
<section class="card">
	<a href="{{post.url}}">
		<div class="title">
			<h2>{{post.title}}</h2>
		</div>
		<div class="author">
			<span class="authorship">{{post.author}}</span>
		</div>
	</a>
</section>
{% endfor %}  
