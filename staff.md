---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

TA office hours are held **Wednesdays 11:00 AM – 12:00 PM** and **Thursdays 2:00 – 3:00 PM**. One TA covers both slots each week, rotating in the order Boyang Zheng → Ziteng Wang → Egor Gikalo. No office hours during Thanksgiving week.

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
