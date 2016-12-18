---
layout: home
permalink: /
title: "Latest Posts"
image:
  feature: lukejohn-500.jpg
---

Type here my really cool ideas!!!


<div class="tiles">
{% for post in site.posts %}
 {% if forloop.index0 <= 3 %}
	{% include post-grid.html %}
 {% endif %}
{% endfor %}
</div><!-- /.tiles -->

<div class="tiles">

<div class="tile">
  <h2 class="post-title">Fixed Content 1</h2>
  <p class="post-excerpt">Takes advantage of native Sass support and data files to make customizing your site easier.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Fixed Content 2</h2>
  <p class="post-excerpt">Designed to put the focus on you and your writing. Headers, navigation, sidebars, and footers have been purposely deemphasized.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Fixed Content 3</h2>
  <p class="post-excerpt">Packed with layouts and modules. Include Disqus comments, social sharing buttons, and table of contents on one or all pages.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Fixed Content 4</h2>
  <p class="post-excerpt">Compatible with popular libraries like <a href="http://bourbon.io">Bourbon</a>, <a href="http://neat.bourbon.io/">Neat</a>, and <a href="http://github.com/octopress/octopress">Octopress</a> to help build and deploy your site with ease.</p>
</div><!-- /.tile -->

</div><!-- /.tiles -->
