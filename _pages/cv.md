---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- TODO: Add a link to downloadable PDF once ready -->
<!-- [Download PDF](/files/cv.pdf) -->

Education
======
<!-- TODO: Fill in your education details -->
* B.S. in Computer Science, North American University, [Year]

Work Experience
======
<!-- TODO: Fill in your work experience -->
* **[Current Position]**
  * [Employer], College Station, TX
  * [Description of duties]

Skills
======
<!-- TODO: Fill in your skills -->
* Programming Languages: TBD
* Frameworks & Tools: TBD
* Research: TBD

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
