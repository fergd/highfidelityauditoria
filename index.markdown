---
layout: home
---
<article class="index-list">
	<h2 class="contents">Contents</h2>
	{% for post in site.posts %}
	<a href="{{post.url}}">
		<section class="card">
			<h3>{{post.title}}</h3>
		<span class="article-type">{{post.type}}</span> by <span>{{post.author}}</span>
		</section>
	</a>
	{% endfor %}  
</article>