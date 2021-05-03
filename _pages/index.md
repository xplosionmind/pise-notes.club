---
layout: page
title: Home
id: home
permalink: /
title: "PISE notes"
---
This is an open set of notes from [***Philosophy, International Studies and Economics***](https://unive.it/pise) classes at [Ca’ Foscari University](https://unive.it) in Venice. More details in the [[About]] page.

<p class="box">
  If you have any suggestion, idea, or you want to report a bug, please <a href="https://github.com/xplosionmind/pise-notes/issues" rel="noopener noreferrer" target="_blank" title="PISE-notes issues on GitHub">open an issue on GitHub</a>. 
</p>

<br>
<br>

## Courses

Start browsing around by entering a course; each course is sub-divided in sections.

- [[Contemporary History]]
- [[Introduction to Philosophy]]
- [[Logic and Philosophy of Science I]]
- [[Mathematics for Social Sciences]]
- [[Introduction to Economics]]
- [[Introduction to Politics]]
- [[History of Economic Thought]]

<ul>
  {% for tag in site.tags %}
    <li><a href="/{{ tag[0] }}" rel="noopener noreferrer" target="_blank" title="{{ tag[0]  | replace: '-', ' '}} index">{{ tag[0]  | replace: '-', ' '}}</a></li>
  {% endfor %}
</ul>

<br>

## Purpose

The final aim of this website is to create an open set of resources for PISE students, allowing us to join forces and study in the most effective way by sharing notes and knowledge across different years of the degree and different areas of interest.

<br>
<br>

## Completeness and reliability

This website is mantained and updated by a first year clumsy PISE student: <mark>its content may be incomplete or not totally reliable</mark>; I keep track of what I lost during the lessons in the [[missing|missing page]]. **Many** topics may be missing but by [[Contribute|contributing]] you can help in filling the gaps.

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

- [Calendari e appelli d’esame](https://www.unive.it/pag/8598/ "Calendari e appelli d’esame")

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
