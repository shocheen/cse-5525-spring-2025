---
layout: home
title: Foundations of Speech and Language Processing
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Foundations of Speech and Language Processing
---

<!-- # {{ site.tagline }} -->
<!-- {: .mb-2 } -->
# {{ site.description }}
#### {{ site.title }} &middot; {{ site.semester }} &middot; {{ site.university }}

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

<!-- <img src="assets/images/crafting_software_header_noBG.png" > 

## Welcome to 17-950 Crafting Software-->

Coming soon

## Prerequisite Knowledge

Coming soon

---

Lectures: MW 1:20-2:40 pm ET 

Lecture Location: TBD

---

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
### Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Code of Conduct

The strength of the university depends on academic and personal integrity. In this course, you must be honest and truthful, abiding by the University Academic Integrity Policy: https://oaa.osu.edu/academic-integrity-and-misconduct


