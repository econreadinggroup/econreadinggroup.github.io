---
layout: page
title: Schedule
description: The weekly event schedule.
---

# Weekly Schedule

<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=Europe%2FMoscow&src=ZmY3NTg2MDMxMzE1ZmYwMjZmZTAzNjY1ZjczNDA4NTI3NmQxNmJjY2NkMjJiN2U3NWZmNTJhOThmYTMxODZkNkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%23795548" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
