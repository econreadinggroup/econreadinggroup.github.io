---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

If you are participating in the reading group course this year, please feel free to book an appointment (by clicking the button below). If you are interested in participating in this course next year, please feel free to email me.


## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
