---
layout: blogarchive
permalink: /ru/
title: Путевой лист
language: ru
translation: de
---

{% assign posts=site.posts  | where:"lang", page.lang%}

 
<div class="tiles">
{% for post in posts %}
 {% if post.language == 'ru' %}
    {% include post-grid.html %}
 {% endif %}
{% endfor %}
</div><!-- /.tiles -->



