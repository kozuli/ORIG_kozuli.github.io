---
layout: default
permalink: /
title: Lebkuchen trifft Design
category: 
---

<div id="mainimage" class="page-lead" style="background-image:url(/images/mainimage/teaser.jpg)">
      <div class="wrap page-lead-content">
        <h1>KOZULI</h1>
        <h2>lebkuchen trifft design</h2>
        <br/><br/>
         <a href="/r/" class="btn-i18n" hreflang="ru">ru</a>
      </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div id="main" role="main">
        <div class="wrap">
        
<br/> 
<div class="tiles">
{% for post in site.posts limit:4%}
	{% if post.language == 'de' %}
		{% include post-grid-min.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles -->  


        </div><!-- /.wrap -->
      </div><!-- /#main -->

