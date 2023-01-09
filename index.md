---
layout: home
title: Home
nav_order: 1
seo:
  type: Course
  name: {{ site.title }}
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## Instructors
{% assign instructors = site.staffers | sort: 'index' %} {% for staffer in instructors %} {{ staffer }} {% endfor %}



## Information
- **Instructor Office Hours**: Monday, 2:10-3:10 PM on Zoom (Book a slot on Canvas)
- **TA office hours**: TBA.

## Description

This graduate-level course focuses on the exciting intersection between machine learning and computational biology. We will cover modern machine learning techniques, including supervised and unsupervised learning, feature selection, probabilistic modeling, graphical models, deep learning, and more. Students will learn the fundamental principles, underlying mathematics, and implementation details of these methods. Through reading and critiquing published research papers, students will learn the applications of machine learning methods to a variety of biological problems in genomics, single-cell analyses, structural biology, and system biology. Students will also learn to implement deep learning models using PyTorch, a popular deep learning library through in-depth programming assignments. In the final project, students will apply what they have learned to real-world data by exploring these concepts with a biological problem that they are passionate about.
This course is appropriate for graduate students or advanced undergraduate students in computer science, bioinformatics, biomedical engineering, mathematics, and statistics. Familiarity with basic linear algebra, statistics, probability, and algorithms is expected. Background knowledge in data analytics and machine learning will be helpful for this course. Students are also expected to have programming experience in Python.

