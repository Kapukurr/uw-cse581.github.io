---
layout: home
title: UW Computing Ethics, Fall 2021
nav_exclude: true
seo:
  type: Course
  name: Computing Ethics
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

 -->

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

## Teaching Assistant

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Course Description

From smart glasses invoking fears of surveillance to social media being flooded by fake news, our society increasingly bears the burden of unintended consequences of technology. As researchers of technology, data scientists, and software developers, we must be aware of the effects that technology has on society and recognize our responsibility to grapple with computer ethics.

In this seminar course, we will discuss the goals of ethics, philosophical approaches to ethics, our own responsibilities, and the many kinds of ethical issues that impact technology and society today. Students will also learn different approaches to anticipating unintended consequences of technology. In a quarter-long research project, they will use these perspectives and approaches to discuss and address issues of applied technologies in areas such as artificial intelligence, user interface design, facial recognition, misinformation, accessibility, and privacy.

## Course Details

**Time:** Tuesdays & Thursdays, 10:00am-11:20am PST

**Location:** CSE2 271

**Flexible office hours:** Email Katharina and Suchin with a few times that work for you! Office hours and any meetings outside of class will be held via Zoom.

**This course is a quals course that counts towards the quals requirement in the human-facing bucket of the CSE PhD program.**

## Quick Links

* [Discussion role sign up sheet](https://docs.google.com/spreadsheets/u/1/d/1OFsnFdCWmfNH2_KaAchdIwk9wFVshqs3JxTu57-UuuI/edit#gid=0)
* [Grading](https://uw-cse599p.github.io/requirements/#grading)
* [Canvas](https://canvas.uw.edu/courses/1512970)


