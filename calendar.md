---
layout: page
title: Calendar & Readings
description: Listing of course modules and topics.
---

# Calendar & Readings

The meetings are held bi-weekly on Mondays at 20:15 GMT+3 on Zoom.


{% for module in site.modules %}
{{ module }}
{% endfor %}
