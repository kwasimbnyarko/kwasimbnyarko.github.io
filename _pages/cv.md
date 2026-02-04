---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

Education
=========

* Ph.D in Computer Science, Virginia Tech, 2028 (expected)
* M.S. in Computer Science, Georgia Tech, 2023
* M.A. in Quantitative Methods in the Social Sciences, Columbia University, 2019
* B.A. in Economics, Education, Emory University, 2017

Work experience
===============

### AI Researcher

* Afiiliation: Republic of Korea Army
* Dates: January 2020 - July 2021

Research Projects
=================

### Using Intelligent Conversational Agents to Empower Adolescents to be Resilient Against Cybergrooming

* Funding: National Science Foundation (NSF)
* Dates: Fall 2024 - Present
* Principal Investigators: Jin-Hee Cho, Pamela J. Wisniewski, Lifu Huang, Sang Won Lee
* Website: [Link](https://wordpress.cs.vt.edu/rylai/)

### AI-Powered Solution for Cyber Scam Prevention: Empowering Community Support for Older Adults

* Funding: Commonwealth Cyber Initiative (CCI) and OpenAI
* Dates: Fall 2025 - Present
* Principal Investigators: Jin-Hee Cho, Junghwan Kim

Teaching
========

* Fall 2024: CS 3654 - Introductory Data Analytics and Visualization (Graduate Teaching Assistant)
* Spring 2025: CS 5804 - Introduction to Artificial Intelligence (Graduate Teaching Assistant)

Publications
============

<ul>
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for post in pubs %}
  <li>{{ post.citation }}{% if post.paperurl %} <a href="{{ post.paperurl }}">[Link]</a>{% endif %}</li>
{% endfor %}
</ul>

Talks
=====

<ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
