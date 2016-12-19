---
layout: home
permalink: /
image:
  feature: lukejohn-500.jpg
---

<div class="page-title">
<h1>Join us</h1>
</div>

<div class="tiles">

  <div class="tile">
    <img src="./images/nochurch1.jpg" width="300" height="300" />
  </div><!-- /.tile -->

  <div class="tile">
    <b>Sunday Worship Schedule</b>
    <p class="post-excerpt">
      <b>8am</b> – Holy Eucharist <br>
      <b>10am</b> – Holy Eucharist with Choir <br>
      <b>11am</b> - Coffee Hour
    </p>
    <b>Wednesday Worship Schedule</b>
    <p class="post-excerpt">
      <b>12pm (noon)</b> - Eucharist and Healing Service
    </p>
  </div><!-- /.tile -->

  <div class="tile">
    <b>Christmas Eve Services</b>
    <p class="post-excerpt">
      <b>5pm</b> - Christmas Family Eucharist <br>
      <b>10:45pm</b> - Choral Music <br>
      <b>11pm</b> - Festival Celebration of the Nativity of our Lord
    </p>
    <b>Christmas Day Service</b>
    <p class="post-excerpt">
      <b>9am</b> - Holy Eucharist <br>
    </p>
  </div><!-- /.tile -->

  <div class="tile">
    <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3017.333498607436!2d-73.62985887204385!3d40.86455485368168!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x318eba7840586f2d!2sSt+Paul&#39;s+Episcopal+Church!5e0!3m2!1sen!2sus!4v1482092682963" width="300" height="225" frameborder="0" style="border:0" allowfullscreen></iframe><br><br><br><br><br>
  </div><!-- /.tile -->

</div><!-- /.tiles -->

<div class="page-title">
<h1>Latest News</h1>
</div>

<div class="tiles">
{% for post in site.categories.parish %}
 {% if forloop.index0 <= 0 %}
  {% include post-grid.html %}
 {% endif %}
{% endfor %}

{% for post in site.categories.outreach %}
 {% if forloop.index0 <= 0 %}
  {% include post-grid.html %}
 {% endif %}
{% endfor %}

{% for post in site.categories.music %}
 {% if forloop.index0 <= 0 %}
  {% include post-grid.html %}
 {% endif %}
{% endfor %}

{% for post in site.categories.school %}
 {% if forloop.index0 <= 0 %}
  {% include post-grid.html %}
 {% endif %}
{% endfor %}

<div class="tile">
  <h2 class="post-title"><a href="./epistle/Dec16Epis.pdf">December 2016 Epistle</a></h2>
  <p class="post-excerpt">Recent news and upcoming events at St. Paul's.</p>
</div><!-- /.tile -->

</div><!-- /.tiles -->

