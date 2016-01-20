---
layout: default
permalink: /mainru/
title: Дизайн и козули
category: mainru
---

<div class="page-lead" style="background-image:url(/images/1600x800.png)">
      <div class="wrap page-lead-content">
        <h1>Козули</h1>
        <h2>Дизайн и козули</h2>
        <a href="/" class="btn-inverse">DE</a>
      </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div id="main" role="main">
        <div class="wrap">
        
<br/>
<div class="tiles">
{% for post in site.posts limit:4%}
	{% if post.langs == 'ru' %}
		{% include post-grid-min.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles -->  


        </div><!-- /.wrap -->
      </div><!-- /#main -->

