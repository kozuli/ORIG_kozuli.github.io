---
layout: archive
permalink: /ru/
title: test
---

{% assign posts=site.posts  | where:"lang", page.lang%}

 <a href="/de/" class="btn-inverse">Alle auf Deutsch</a>
 
<div class="tiles">
{% for post in posts %}
 {% if post.language == 'ru' %}
    {% include post-grid.html %}
 {% endif %}
{% endfor %}
</div><!-- /.tiles -->



