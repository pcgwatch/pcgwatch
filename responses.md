--- 
layout: post
author: PCG Watch
title: Rebuttals and Responses
---
This page is reserved for any official responses from the PCG or its members. We would love to see people engaging in debate. 

Although PCG members believe they have good arguments for their beliefs, they are very rarely challenged on them. Ministers never debate other denominations on doctrines or prophetic interpretations. We believe that this is because their arguments are so flimsy that they would crumble under the smallest public examination. 

If any PCG members would like to post official rebuttals of any articles on this site, we *will* publish them here!

<hr>

<ul>
    {% for category in site.categories %}
        {% if category[0] == "responses" %}
            {% for post in category[1] %}
                <li style="text-align: left;" class="smalltext"><a href="{{ post.url }}">{{ post.title }}</a></li>
            {% endfor %}
        {% endif %}        
    {% endfor %}
</ul>
