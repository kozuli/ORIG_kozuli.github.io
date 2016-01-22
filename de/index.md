---
layout: archive
permalink: /de/
title: test
language: de
---

{% assign posts=site.posts  | where:"lang", page.lang%}

<a href="/ru/" class="btn-inverse">Все на русском</a>

<div class="tiles">
{% for post in posts %}
 {% if post.language == 'de' %}
    {% include post-grid.html %}
 {% endif %}
{% endfor %}
</div><!-- /.tiles -->


