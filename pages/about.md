---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Salutations! I'm **{{ site.author.name }}** :wave:,<br>
I am a software engineer on the Data Science Platform team at Klaviyo. Have a glimpse of my day to day [here](blog.html).

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>