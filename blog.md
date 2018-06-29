---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
title: Blog
order: 4
---

{% for post in site.posts %}
  <div class="entry">
  	<div class="entrytitle">
  		<h2><a href="{{ post.url }}">{{ post.title }}</a> | <span class="author">{{ post.authornames }}</span></h2> 
  		<h3>{{ post.date | date_to_string }}</h3>
  	</div>
  	
  	<div class="entrybody">
  	  {{ post.excerpt }}
  	</div>
  	
  </div>

{% endfor %}