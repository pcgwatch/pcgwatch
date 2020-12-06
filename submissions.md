---
layout: post
title: Submissions
author: PCG Watch
---
This page is dedicated to any articles submitted by PCG members or ex-members. Before the establishment of PCG Watch, we had been sent numerous articles from such members who are discovering things about the PCG on their own. 

Some of these articles and studies are about doctrines they believe the PCG is wrong about, or differences between WCG and PCG doctrines, or critiques of specific issues they believe are important. Often these studies by members are done in good faith, and they expect their discoveries or problems to be discussed. Instead, they are suspended, disfellowshipped, or marked just for bringing them up. This page will hopefully be a place to voice some of these discussions.

<hr>

<ul>
    {% for category in site.categories %}
        {% if category[0] == "submission" %}
            {% for post in category[1] %}
                <li style="text-align: left;" class="smalltext"><a href="{{ post.url }}">{{ post.title }}</a></li>
            {% endfor %}
        {% endif %}        
    {% endfor %}
</ul>
