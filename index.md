---
title: "Analog Moments"
image: "/assets/img/cover.jpg"
---
<div class="moment-wrapper">
	{% for moment in site.moments %}
		<div class="moment-preview">
			<a href="{{ moment.url | relative_url }}">
				<img src="{{ moment.image | relative_url }}" /></a>
			<a href="{{ moment.url | relative_url }}">#{{moment.title}}</a>
		</div>
	{% endfor %}
</div>