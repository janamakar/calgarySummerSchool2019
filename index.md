---
layout: default
---

{% include figure.html file="wgLogoHighRes.jpg" alt="intro image here" width="85%" %}

# Research computing summer school

## Monday May 27th to Thursday May 30th, 2019

This May, [WestGrid](https://www.westgrid.ca) is bringing its four-day Research Computing Summer School
to the University of Calgary. Courses will explore introductory and advanced topics in high performance
computing and parallel programming, machine leaning, research computing with Python / R / MATLAB / C /
C++, and scientific visualization.

For full course details, please check [the program]({{ site.baseurl }}/1-program.html). We encourage
anyone interested in building knowledge and skills for computational research to attend the
school. Researchers in all disciplines and skill levels are welcome to register.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | prepend: site.url }}){% endif %}
{% endfor %}
</div>
