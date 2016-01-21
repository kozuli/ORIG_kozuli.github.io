---
layout: media
excerpt: Thundercats deep v sartorial, main pic post
image:
  feature: test/sample-pic-post/1200x450.png
  teaser: test/sample-pic-post/400x250.png
  thumb: test/sample-pic-post/80x80.png
  credit: KOZULI #name of the person or site you want to credit
  creditlink: http://vk.com #url to their site or licensing
title: "pic post"
published: true
langs: de
category: de
published: false
---

<div class="tiles">
tra lala
</div><!-- /.tiles -->


{% include featherlight-gallery.html %}
<section data-featherlight-gallery data-featherlight-filter="a">
  {% for i in (1..8) %}<a href="/images{{page.url}}900x450-{{ i }}.png"><img src="/images{{page.url}}80x80-{{ i }}.png"></a>{% endfor %}
</section>

<section data-featherlight-gallery data-featherlight-filter="a">
<figure class="third">
	<a href="/images{{page.url}}900x450-1.png"><img src="/images{{page.url}}400x250.png"></a>
	<a href="/images{{page.url}}900x450-1.png"><img src="/images{{page.url}}400x250.png"></a>
	<a href="/images{{page.url}}900x450-1.png"><img src="/images{{page.url}}400x250.png"></a>
	<figcaption>Caption describing these three images.</figcaption>
</figure>
</section>

<section data-featherlight-gallery data-featherlight-filter="a">
<figure class="half">
	<a href="/images{{page.url}}900x450-1.png"><img src="/images{{page.url}}400x250.png"></a>
	<a href="/images{{page.url}}900x450-1.png"><img src="/images{{page.url}}400x250.png"></a>
	<figcaption>Caption describing these two images.</figcaption>
</figure>
</section>

<section data-featherlight-gallery data-featherlight-filter="a">
<figure>
	<a href="/images{{page.url}}900x450-1.png"><img src="/images{{page.url}}900x450-1.png"></a>
	<figcaption>Caption describing these image.</figcaption>
</figure>
</section>

   
 <section data-featherlight-gallery data-featherlight-filter="a">
  <ul class="th-grid">
  {% for i in (1..8) %}
    <li><a href="/images{{page.url}}900x450-{{ i }}.png"><img src="/images{{page.url}}400x250-{{ i }}.png"></a></li>
  {% endfor %}
  </ul>
  </section>
 

 <nav>
     <ul>
       <li><a href="#link-1">Link 1</a></li>
       <li><a href="#link-2">Link 2</a></li>
       <li><a href="#link-3">Link 3</a></li>
     </ul>
   </nav>
   
 <a href="#" class="btn">Default Button</a>
 
Thundercats deep v sartorial, locavore shoreditch typewriter PBR&B kinfolk gastropub YOLO raw denim fingerstache affogato. Helvetica freegan jean shorts cold-pressed, retro shoreditch master cleanse messenger bag dreamcatcher. Mlkshk paleo ennui, brooklyn kale chips heirloom microdosing skateboard cold-pressed. Blue bottle cardigan bespoke, DIY tousled lumbersexual austin venmo seitan chambray pop-up waistcoat synth street art four dollar toast. Hoodie blue bottle synth pickled, readymade williamsburg godard. Bespoke godard flannel, banjo venmo yuccie kale chips cray iPhone. Leggings godard mlkshk, waistcoat dreamcatcher fixie occupy irony trust fund sustainable drinking vinegar.

Vinyl bushwick slow-carb 90's, tattooed organic cold-pressed master cleanse tumblr fixie. Skateboard franzen cliche, lomo shoreditch narwhal occupy 8-bit. Semiotics wolf you probably haven't heard of them, meggings ethical deep v shoreditch kinfolk banh mi pork belly umami skateboard flannel twee polaroid. DIY post-ironic intelligentsia brunch cronut bespoke, freegan pabst mlkshk mustache kitsch. Pug shabby chic brooklyn, YOLO scenester small batch kitsch hammock. Ramps bespoke pitchfork, lomo cardigan 8-bit chillwave helvetica deep v fanny pack pug heirloom. Seitan literally sriracha tofu, church-key aesthetic neutra bicycle rights.


{% include image-credit.html %}
