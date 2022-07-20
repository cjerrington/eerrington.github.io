---
layout: default
---

<!-- Section -->
<section>
	<header class="major">
		<h2>Services</h2>
	</header>
	<div class="features">
		{% for service in site.data.services %}
			<article>
			<i class="icon {{ service.img }}"></i>
				<div class="content">
					<h3>{{ service.title }}</h3>
					<p>{{ service.desc }}</p>
				</div>
			</article>
		{% endfor %}
	</div>
</section>

<!-- Section >
<section>
	<header class="major">
		<h2>Things for you</h2>
	</header>
	<div class="posts">

  	{% for post in site.posts %}
  		<article>
			<a href="{{ post.url }}" class="image"><img src="{{ post.image }}" alt="" /></a>
			<h3>{{ post.title }}</h3>
			<p>{{ post.excerpt }}</p>
			<ul class="actions">
				<li><a href="{{ post.url }}" class="button">More</a></li>
			</ul>
		</article>
  	{% endfor %}
	</div>
</section-->
