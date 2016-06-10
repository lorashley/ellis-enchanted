---
layout: page
permalink: /index2
---

<div class="what">
	<a href="#what"></a>
<hr>
	<h2>Recent Post</h2>
	<table><tr>
	{% for post in site.posts limit:3 %}
	<td>
	
	<article class="{% cycle '6u', '6u$' %} 12u(small) excerpt">
	<header>
	<a href="{{ site.url }}{{ post.url }}">{{ post.title | truncatewords: 5}}</a></div>
	<img src="{{ post.image }}" width="200px"></header>
	<p>{{ post.date | date: "%b %-d" }}: 
	{{ post.content | strip_html | truncatewords: 50 }}</p>
	</article>
	
	</td>
	{% endfor %}
	</tr></table>

</div>


<div class="who">
	<a href="#who"></a>
	<hr>
	<img src="/img/avatar.jpg" alt="" class="avatar">
	<h2>About Me</h2>
	<p>Hello! I’m Lauren. By day I go by the title of imagineer (not affiliated to Disney Imagineers, nor have I proposed this 
	title to my management) and by night I’d fall into the wife and mother of 2 (kitties that is). If you were to meet me, you 
	would hear me say these things about myself (potentially multiple times. Yes, I am proud): </p>

	<ul>
	<li>South Florida native</li>
	<li>Parents from Trinidad</li>
	<li>Met my hubs in University</li>
	<li>Home is now New England</li>
	<li>Slowly evolving into a crazy cat lady</li>
	<li>Cofounder of a paper product duo 
	<a href="https://www.etsy.com/people/coastalcollectivepc" target="_blank">
	Coastal Collective</a> (Items to be added soon!)</li>
	</ul> 
	

	<p>Ellis Enchanted refers to my home. But really it’s a space for everything inside and outside of the physical walls. I like to think that everywhere I go, it becomes a home to me, even if only in its brevity. Enjoy your stay.
	</p>
</div>

<div class="where">
	<a href="#where"></a>
	<img src="/img/homes.jpg" class="location">
</div>
