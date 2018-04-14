<div class="moment-wrapper">
	{% for moment in site.moments %}
		<div class="moment-preview">
			<a href="/moments/{{moment.title}}"><img src="/assets/img/{{moment.title}}.jpg" /></a>
			<a href="/moments/{{moment.title}}">#{{moment.title}}</a>
		</div>
	{% endfor %}
</div>