---
layout: default
title: Teaching and Outreach
group: navigation
nav_title: Teaching and Outreach
nav_ord: 4
---

<div class="skills_holder">
    <!--Information about teaching activities-->
    <div class="column">
        <h2>Teaching:</h2>
        <p>Prof. Banerjee teaches several courses at IISER-Kolkata.</p>
        {% for course in site.data.teaching %} 
            <span class="par">{{ forloop.index }}. <a target="_blank" href="{{ course.url }}"><em>{{ course.course-title }}</em></a></span><br>
            <br>
        {% endfor %}    
        
        <p class="par">His lecture series, <a target="_blank" href="https://www.youtube.com/watch?v=8U3QvviaMJQ&amp;list=PLD074EEC1EBEFAEA5"><em>Dynamics of Physical Systems</em></a> and <a target="_blank" href="https://www.youtube.com/watch?v=mkfU9zVNGkQ&amp;list=PL465CF583900B36A3"><em>Chaos, Fractals and Dynamical Systems</em></a> are also available online.</p>
    </div>
    
    
    <!--Information about outreach activities-->
    <div class="column column-add">
        <h2>Outreach:</h2>
        <p>Prof. Banerjee is also involved in several outreach programmes for promoting science education, awareness and scientific thinking in India.</p>
        {% for act in site.data.outreach %} 
            <span class="par">{{ forloop.index }}. <a target="_blank" href="{{ act.url }}"><em>{{ act.title }}</em></a>: {{ act.description }} </span><br>
            <br>
        {% endfor %}
    </div>
</div>

       