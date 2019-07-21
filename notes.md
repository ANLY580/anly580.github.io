---
title: Course Notes
layout: page
menuItem: Course Notes
menuPosition: 2
---

Official weekly notes are posted on [Canvas](https://georgetown.instructure.com).

<ol>
{% assign syllabus = (site.syllabus | sort: "week") %}
{% for week in syllabus %}
  <li>
  	<a href="{{ site.baseurl }}{{ week.url }}">{{ week.title }}</a>
    <b>({{ week.day }})</b>
  	{% for tag in week.tags %}
  		#{{ tag }}
  	{% endfor %}
  	</li>
{% endfor %}
</ol>
