---
layout: default
permalink: /
title: Pfefferkuchen trifft Design
---

<div class="page-lead" style="background-image:url(/images{{page.url}}1600x800.png)">
      <div class="wrap page-lead-content">
        <h1>Kozuli</h1>
        <h2>Pfefferkuchen trifft Design</h2>
      </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div id="main" role="main">
        <div class="wrap">
        
<br/>
<div class="tiles">
{% for post in site.posts limit:4%}{% include post-grid-min.html %}{% endfor %}
</div><!-- /.tiles -->  


        </div><!-- /.wrap -->
      </div><!-- /#main -->

