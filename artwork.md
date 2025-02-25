---
title: Artwork
layout: rest
description: I try to work sometimes.
type: parent
order: 2
---

{% include categories.html category="artwork" %}

<!-- <div class="section main">
	<div class="container">
		{% assign img_folder = '/assets/img/' %}
		{% assign mypages = site.pages | where: "type", "artwork" %}
		{% for page in mypages %}
		{% assign src_img = img_folder | append: page.title | append: '.jpg' %}
		<a class="button" href="{{ page.url | relative_url }}"> <img src="{{ src_img | relative_url }}" width="200" height="132">
		</a>
		{% endfor %}
	</div>
</div> -->