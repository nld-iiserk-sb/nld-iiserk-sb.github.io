---
layout: default
title: Research
group: navigation
nav_title: Research
nav_ord: 2
---


<div class="skills_holder">    
    <h2>Ongoing Projects :-</h2>
    <p class="par">We currently have experimental, theoretical and computational projects related to the application of nonlinear dynamics in diverse fields. Please visit our <a href="leader.html"><em>People </em></a>page for more details.</p>
    
<!--Loop through project title in the '_data/projects.yml' datafile-->
    {% for item in site.data.projects %}
        <span>{{ forloop.index }}. {{ item.title }}</span><br><br>
    {% endfor %}
            

    <h2>Selected Publications :-</h2>
    <p><font color="FFFFFF">BOOKS</font></p>
<!--Loop through books in the '_data/books.yml' datafile-->
    {% for item in site.data.books %}
        <span>{{ forloop.index }}. {{ item.authors }},{{ item.title }}, {{ item.publisher }}, {{ item.year }}.</span><br><br>
    {% endfor %}


    <p><font color="FFFFFF">JOURNAL ARTICLES</font></p>
<!--Loop through journal articles in the '_data/articles.yml' datafile-->    
    {% for item in site.data.articles %}
        <span>{{ forloop.index }}. 
            {% for aut in item.authors %}
                {{ aut.author }},
            {% endfor %}
            "{{ item. title}}",<strong>{{ item.journal }}</strong>, {{ item.volume }}, {{ item.no }}, pp. {{ item.pages }}, {{ item.date }}. 
        </span><br><br>
    {% endfor %}
    
    <span class="par">The complete list of publications is available at Prof. Banerjee's&nbsp;<a target="_blank" href="http://www.researcherid.com/rid/F-8162-2011"><em> Researcher ID</em></a> page.</span><br>
</div>
        