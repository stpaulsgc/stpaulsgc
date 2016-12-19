---
layout: archive
title: "Musical Activities"
image:
  feature: choir.jpg
  teaser:
---

There many concerts that happen here at St. Paul's. More news will be posted as the site progresses. Also, don't forget we have choir rehearsal at 9:15am on Sunday mornings!

# Recent Posts

<div class="tiles">
{% for post in site.categories.music %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->