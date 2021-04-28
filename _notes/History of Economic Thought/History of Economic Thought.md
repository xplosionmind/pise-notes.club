---
date: 2021-04-20T07:46:07.988037+02:00
updated: 2021-04-20T07:46:07.988037+02:00
tags: hoet
---
Lecture notes from [History of Economic Thought].

<ol>
	{% for p in site.notes %}
		{% if page.tags == p.tags %}
			{% if page.url != p.url %}
				<li>
					<a href="{{ p.url }}" title="{{ p.title }}">{{ p.title }}</a>
				</li>
			{% endif %}
		{% endif %}
	{% endfor %}
</ol>

[History of Economic Thought]: https://www.unive.it/data/course/332311/ "History of Economic Thought on Ca’Foscari website"
