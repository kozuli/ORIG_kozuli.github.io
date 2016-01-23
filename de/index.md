---
layout: blogarchive
permalink: /de/
title: Unterwegs durch die Tage
language: de
translation: ru
---

{% assign posts=site.posts  | where:"lang", page.lang%}


<div class="tiles">
{% for post in posts %}
 {% if post.language == 'de' %}
    {% include post-grid.html %}
 {% endif %}
{% endfor %}
</div><!-- /.tiles -->


