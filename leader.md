---
layout: default
title: People
group: navigation
nav_title: People
nav_ord: 3
category: leader
cat_ord: 1
---

<h2>LAB MEMBERS</h2>

{% include people_nav_bar.html class="sub_nav" pages=site.data.people_categories category=page.category %}

{% include people_box_loop.html category=page.category %}


