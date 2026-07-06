---
layout: default
title: Practice Areas
description: Explore Gary Koo’s practice areas, including business transactions, intellectual property protection, and high-stakes commercial dispute matters.
---

# Practice Areas

<div class="d-flex flex-column align-items-center">
	{% for service in site.data.services %}
		<div class="card my-3">
		  	<div class="card-body">
		  		<h5 class="card-title">{{ service.name }}</h5>
		  		<p class="card-text">{{ service.description }}</p>
		  	</div>
		</div>
	{% endfor %}
</div>
