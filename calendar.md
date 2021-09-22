---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

The class schedule is detailed below, and is subject to change. We will announce any changes during class and on Canvas.

All readings are required, unless they are tagged with **Optional**{: .label .label-green }.

[Reading responses](https://uw-cse599p.github.io/requirements/#reading-responses-and-discussion) are also required, unless explicitly noted.

Reading responses are due by **6pm the day before class**.

Milestones are due before **9am on the morning of the class**.

{% for module in site.modules %}
{{ module }}
{% endfor %}
