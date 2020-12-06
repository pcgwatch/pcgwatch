---
layout: post
title: Prophecies
author: PCG Watch
---
Armstrong and Flurry are a duo that have made many prophecies. Instead of forgetting them or explaining them away, we want to analyze their accuracy and remind you if they did not come true. 

We also want to ask questions about the nature of prophecy. Is prophecy really "dual" like Armstrong said? Was every major and minor prophet *really* talking about Armstrong, Flurry, the PCG, and the so-called "Laodiceans"? Or have these two just been shoehorning their own preoccupations into the words of ancient Hebrews?

This page collects all our articles on the nature and accuracy of Armstrong and Flurry's view of prophecy.

<hr>

<ul>
    {% for category in site.categories %}
        {% if category[0] == "prophecy" %}
            {% for post in category[1] %}
                <li style="text-align: left;" class="smalltext"><a href="{{ post.url }}">{{ post.title }}</a></li>
            {% endfor %}
        {% endif %}        
    {% endfor %}
</ul>
