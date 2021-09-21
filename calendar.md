---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

The class schedule is detailed below, and is subject to change. We will announce any changes during class and on this website.

All readings are required for each class, unless they are tagged with **Optional**{: .label .label-green }. Reading responses are also always required, unless otherwise noted.


{% for module in site.modules %}
{{ module }}
{% endfor %}
