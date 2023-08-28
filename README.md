---
layout: home
title: Home
permalink: /:path/
nav_order: 1
seo:
  type: Course
  name: Home
---

# Welcome!
This is the first-ever iteration of a DeCal designed to provide aspiring linguists with an easily accessible introduction to computing. We highly recommend students to have taken Linguistics 100 or equivalent. The course is designed for students with no programming experience.

We will meet on Tuesdays at 5-6:30pm in [Latimer 105](https://goo.gl/maps/Pm1BaTQLF4zWsKRV9). 
<br>
We will also hold hybrid office hours on Fridays at 1-3pm. You may attend in-person in [the Linguistics Lounge (Dwinelle 1202)](https://goo.gl/maps/ijwJZkd7UjrLRtNU7), or remotely through the class Discord server.
## Calendar
{% for module in site.modules %}
{{ module }}
{% endfor %}
## Staff
Our faculty advisor is [Prof. Terry Regier](https://lclab.berkeley.edu/regier/).
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
