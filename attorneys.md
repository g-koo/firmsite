---
layout: default
title: Attorneys
---

# Attorneys
<div class="card-deck">
	{% for attorney in site.data.attorneys %}
		  <div class="card my-3" style="min-width: 30%;">
		  		<div class="card-body">
		  			<h5 class="card-title">{{ attorney.name }}</h5>
					<h6 class="card-title2">{{ attorney.title }}</h6>
		  			<p class="card-text">{{ attorney.bio }}</p>
		  		</div>
				<ul class="list-group list-group-flush">
				    <li class="list-group-item">Email: {{ attorney.email }}</li>
				</ul>
		  </div>
	{% endfor %}
</div>	
