---
layout: post
title: The Bible
author: PCG Watch
---
The PCG and Gerald Flurry have a very specific view and interpretation of the Bible. Although their view is only one of hundreds, they act as if these other views are only held my the malicious or the deceived. 

How much does Gerald Flurry really know about the Bible and Christianity? Do they misrepresent other Christians and do they misrepresent the Bible? Does their view of biblical inerrancy hold up to scrutiny? Or, like the rest of well-meaning people in the Christian world, can one have a different opinion and still be genuine? 

This page collects all our articles on the Bible and the PCG's view of it.

<hr>

<ul>
    {% for category in site.categories %}
        {% if category[0] == "bible" %}
            {% for post in category[1] %}
                <li style="text-align: left;" class="smalltext"><a href="{{ post.url }}">{{ post.title }}</a></li>
            {% endfor %}
        {% endif %}        
    {% endfor %}
</ul>
