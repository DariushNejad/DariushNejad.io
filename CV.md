---
layout: page
permalink: /CV/index.html
title: CV
---


<section class="list">
    {% for post in site.posts %}
        {% if post.projects %}
            <div class="item {% if post.star == true %}star{% endif %}">
                <a class="url" href="{{ site.url }}{{ post.url }}">
                    {{ post.jemoji }}<h3 class="title">{{ post.title }}</h3>
                </a>
            </div>
        {% endif %}
    {% endfor %}
</section>

Im gonna try and see if this page works 1054



