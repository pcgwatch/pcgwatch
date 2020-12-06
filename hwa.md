---
title: Herbert W. Armstrong
layout: post
author: PCG Watch
---
Herbert W. Armstrong was a man who told people throughout his whole life that Jesus Christ's return would be in a "few short years." He, like many other preachers within 7th-Day Adventist circles, believed that the Lost Ten Tribes of Israel were to be found in the United States and Britain. He believed that mainstream Christianity had been corrupted, its teaching hidden, revealed only to a few--himself *obviously* being included.

How accurate were HWA's doctrines and prophecies? Were his claims about the "Lost Century," British Israelism, or the Assyria-Germany connection historically accurate? How genuine were his meetings with "world leaders"? Or was he prone to exaggeration? Why was his church hugely rich but somehow always in need of massive offerings from members? 

This page collects all our articles about these questions, and more.

<hr>

<ul>
    {% for category in site.categories %}
        {% if category[0] == "hwa" %}
            {% for post in category[1] %}
                <li style="text-align: left;" class="smalltext"><a href="{{ post.url }}">{{ post.title }}</a></li>
            {% endfor %}
        {% endif %}        
    {% endfor %}
</ul>
