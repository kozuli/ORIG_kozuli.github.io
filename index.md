---
layout: default
permalink: /
title: Lebkuchen trifft Design
category: 
---

<div class="page-lead" style="background-image:url(/images{{page.url}}1600x800.png)">
      <div class="wrap page-lead-content">
        <h1>Kozuli</h1>
        <h2>Lebkuchen trifft Design</h2>
         <a href="/r/" class="btn-inverse">RU</a>
      </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div id="main" role="main">
        <div class="wrap">
        
<br/>
<div class="tiles">
{% for post in site.posts limit:4%}
	{% if post.langs == 'de' %}
		{% include post-grid-min.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles -->  


        </div><!-- /.wrap -->
      </div><!-- /#main -->

