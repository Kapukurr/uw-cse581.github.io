---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

The class schedule is detailed below, and is subject to change. We will announce any changes during class and on this website.

All readings are required for each class, unless they are tagged with **Optional**{: .label .label-green }. 

In addition, some classes have a **Milestone**{: .label .label-purple } tag. Check the corresponding links for more information on those milestone requirements.

{% for module in site.modules %}
{{ module }}
{% endfor %}
