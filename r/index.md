---
layout: default
permalink: /r/
title: Дизайн и козули
category: r
---

<div id="mainimage" class="page-lead" style="background-image:url(/images/mainimage/teaser.jpg)">
      <div class="wrap page-lead-content">
        <h1>КОЗУЛИ</h1>
        <h2>дизайн и козули</h2>
        <br/><br/>
        <a href="/" class="btn-i18n" hreflang="de">de</a>
      </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div id="main" role="main">
        <div class="wrap">
        
<br/>
<div class="tiles">
{% for post in site.posts limit:4%}
	{% if post.language == 'ru' %}
		{% include post-grid-min.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles -->  


        </div><!-- /.wrap -->
      </div><!-- /#main -->

