---
layout: post
title: Gerald Flurry
author: PCG Watch
---
Gerald Flurry is the self-proclaimed King of England, a man who believes that the Christian god speaks to him both through scripture and sometimes in dreams. 

How accurate are this man's teachings? What kind of grasp does he have on the Bible and its history? Should you trust him when he says Jesus Christ will return in a "few short years"? Should you obey him when he tells you to stop having contact with family and friends? 

This page collects all our articles on Gerald Flurry and his teachings. We examine whether his prophecies come true, whether he has his history correct, whether he has changed his teachings from Herbert W. Armstrongs, whether he misquotes scriptures, whether the biblical positions he attributes to himself are accurate, and more. 

<hr>

<ul>
    {% for category in site.categories %}
        {% if category[0] == "grf" %}
            {% for post in category[1] %}
                <li style="text-align: left;" class="smalltext"><a href="{{ post.url }}">{{ post.title }}</a></li>
            {% endfor %}
        {% endif %}        
    {% endfor %}
</ul>
