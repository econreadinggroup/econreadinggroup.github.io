---
layout: page
title: Schedule
description: The weekly event schedule.
---

# Weekly Schedule

<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=Europe%2FMoscow&src=ZS52LmJyb25uaWtvdkBnbWFpbC5jb20&src=ZmY3NTg2MDMxMzE1ZmYwMjZmZTAzNjY1ZjczNDA4NTI3NmQxNmJjY2NkMjJiN2U3NWZmNTJhOThmYTMxODZkNkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=YWRkcmVzc2Jvb2sjY29udGFjdHNAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&src=Y2xhc3Nyb29tMTA2NTExOTI3MTg0MDU0NTE4MDA1QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&src=cnUucnVzc2lhbiNob2xpZGF5QGdyb3VwLnYuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&color=%23039BE5&color=%23795548&color=%2333B679&color=%23202124&color=%230B8043" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>


{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
