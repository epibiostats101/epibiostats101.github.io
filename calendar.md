---
layout: page
title: Home
nav_order: 1
description: Listing of course modules and topics.
---

# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

# Calendar

{% for module in site.modules %}
{{ module }}
{% endfor %}
