---
layout: home
title: UW CSE Computing Ethics, Winter 2024 
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

## Quick Links

* [Discussion lead sign up sheet](https://docs.google.com/spreadsheets/u/1/d/1OFsnFdCWmfNH2_KaAchdIwk9wFVshqs3JxTu57-UuuI/edit#gid=0) (We will give you access at the start of the quarter)
* [Grading](https://uw-cse581.github.io/requirements/#grading)
* [Canvas](https://canvas.uw.edu/courses/1696045)


## Course Details

**Time:** Tuesdays & Thursdays, 10:00am-11:20am PST

**Location:** CSE2 271

**Flexible office hours:** Email Katharina and Alice with a few times that work for you! Office hours and any meetings outside of class will be held via Zoom.

**This course is a quals course that counts towards the quals requirement in the human-facing bucket of the CSE PhD program.**


## Course Description

From smart glasses invoking fears of surveillance to social media being flooded by fake news, our society increasingly bears the burden of unintended consequences of technology. As researchers of technology, data scientists, and software developers, we must be aware of the effects that technology has on society and recognize our responsibility to grapple with computer ethics.

In this seminar course, we will discuss the goals of ethics, philosophical approaches to ethics, our own responsibilities, and the many kinds of ethical issues that impact technology and society today. Students will also learn different approaches to anticipating unintended consequences of technology. In a quarter-long research project, they will use these perspectives and approaches to discuss and address issues of applied technologies in areas such as artificial intelligence, user interface design, facial recognition, misinformation, accessibility, and privacy.

## Course type and structure
The course is designed to be a very interactive and discussion-based seminar. There will be occasional lectures, in-class presentations, and discussions of course projects.

Part of the course will require you to conduct a quarter-long research project on the topic of computer ethics, such as compiling counter data to existing datasets, conducting a technical audit, interview studies, value sensitive design analyses, or similar to quantify disparities, etc. These research projects should be done in pairs. For each research project, you are required to present your results in a written paper draft and orally in class. 

Most lectures will be structured the following way:

* ~40 minutes of paper discussions, led by a [discussion lead](https://uw-cse581.github.io/discussion_roles/#reporter-aka-discussion-lead)
* ~40 minutes of one of the following:
    * an in-class activity (e.g., applying a framework for anticipating unintended consequences of technology to a specific product);
    * A talk by an invited speaker
    * Idea and project fairs (each team presents their projects)
    * Peer-feedback sessions on class projects


## Learning goals

After taking this course, students will know: 

* The appropriate terminology to discuss and think critically about technology; 
* Goals and philosophical approaches to ethics and how to apply these in multifaceted discussions of technology; 
* The key literature on societal and environmental unintended consequences of technology; 
* Our responsibilities as researchers in a variety of fields; 
* How to apply tools and strategies for anticipating unintended consequences of technology, such as technical audits, tarot cards of tech, value sensitive design analyses, the delphi method, etc. 
* How to conduct a research project on the topic of computer ethics to gain a deep understanding of ethical issues surrounding a specific technology. 

## Pre-requisites and who this course is for

There are no pre-requisites for this class. The course is designed for UW CSE graduate students (in any area of CS research) who are interested in learning about ethics and how to anticipate potential undesirable consequences of computing innovations. Basically, if you produce and use data, develop technology, and are part of our society, then this course is for you. 


## Course Inspirations

This syllabus was inspired by many other ethics classes offered at the UW and elsewhere, including Jared Moore and Dan Grossman’s [CSE492e](https://courses.cs.washington.edu/courses/cse492e/20au/) (UW), Casey Fiesler’s [INFO 4601](https://informationethicspolicy.wordpress.com/) (UC Boulder), Amy Bruckman’s [CS 4863](https://www.cc.gatech.edu/~asb/teaching/4863/fall2019/) (Georgia Tech), Joi Ito and Jonathan Zittrain’s [MAS.S64](https://www.media.mit.edu/courses/the-ethics-and-governance-of-artificial-intelligence/) (MIT). Thanks to Jared Moore, Dan Grossman, and Krzysztof Gajos for sharing materials and thoughts on this class!



