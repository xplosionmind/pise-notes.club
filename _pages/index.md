---
layout: page
title: Home
id: home
permalink: /
title: "PISE notes"
---
<style>
content h1 {
	display: none;
}
</style>
This is an open set of notes from [***Philosophy, International Studies and Economics***](https://unive.it/pise) classes at [Ca’ Foscari University](https://unive.it) in Venice. More details in the [[About]] page.

<br>

## Courses

### First year

<ul>
	{% for course in site.notes %}
		{% if course.layout == 'course' and course.year == 1 %}
			<li><a href="{{ course.url }}" title="{{ course.course }} notes">{{ course.course }}</a></li>
		{% endif %}
	{% endfor %}
</ul>

<br>

### Second year

<ul>
	{% for course in site.notes %}
		{% if course.layout == 'course' and course.year == 2 %}
			<li><a href="{{ course.url }}" title="{{ course.course }} notes">{{ course.course }}</a></li>
		{% endif %}
	{% endfor %}
</ul>

<br>
<br>

## Purpose

The sole purpose of this website is to create an open set of resources for PISE students, allowing us to join forces and study in the most effective way by sharing notes, knowledge, and tips.

<br>
<br>

## Completeness and reliability

This website is mantained and updated by a first year clumsy PISE student: <mark>its content may be incomplete or inconsistent and it <strong>should not</strong> be considered exhaustive</mark>; I keep track of what I lost during the lessons in the [[missing|missing page]]. **Many** topics may be missing but you can [[Contribute]] by helping to fill the gaps.

<br>
<br>

## Legend

Notes may contain several gaps and inconsistent passages; such unclear parts are marked by some symbols:

- `+++`: missing parts
- `???`:
	- unclear passages
	- questions
- `grm`: doubts about grammar
- `+++S`: copy from slides
- `“+++”`: exact citation of the professor missing
- `(+++)`: there's a missing knowledge to what has just been written

<br />
<br />

## Useful links

- [Shared Dropbox] (this website has no affiliation with this link and content uploaded does not correspond to what is on pise-notes.tk)
- [Calendari e appelli d’esame](https://www.unive.it/pag/8598/ "Calendari e appelli d’esame")

[Shared Dropbox]: https://www.dropbox.com/s/03ri6wyggpj0522/PISE.zip "PISE.zip"
