---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

I grew up in San Diego CA got a BA in computer science from the University of Colorado at Boulder and will be staying at CU to pursue a masters in mechanical engineering. I am currently a member of the **H**uman **I**nteraction and **RO**botics (HIRO) research group at CU and have focused my studies on robotics, autonomy and intelligent control. My dream job is developing intelligent and interactive mechatronic/robotic systems. Some of my hobbies include snowboarding, pickup sports, cooking and traveling.

{% capture carousel_images %} 
/img/DadAndYogi.jpg
/img/WithYogi.jpeg
/img/Lacrosse.jpg
/img/SandDunes.jpg
{% endcapture %} 
{% include elements/carousel-custom.html %}

<div class="row">
{% include about/skills.html title="Programming Languages" source=site.data.programming-skills %}
{% include about/skills.html title="Operating Systems" source=site.data.operating-systems %}
{% include about/skills.html title="Applications" source=site.data.applications %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
