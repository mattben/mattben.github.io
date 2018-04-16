---
layout: default
title: Home
---

<style type="text/css">
  div.hero-unit {
    position: relative;
    z-index: 1;
  }
  div.hero-unit div.hero-bg {
    position: absolute;
    z-index: -1;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    opacity: .15;
    background: url(media/images/cam.jpg) center center no-repeat;
    width: 100%;
    height: 100%;
  }
</style>

{% include hero.html %}
<div class="span12">
  <div class="row">
    <div class="span4">
      <center>
      <h2>LLNL</h2>
      <img src="media/images/llnl-blue.png" class="thumbnail" />
      <p>Currently employed at Lawrence Livermore National Laboratory as a <i>Computer Scientist / Math Programmer</i></p>
      <p><a class="btn" href="llnl.html">View details</a></p>
      </center>
    </div>
    <div class="span6">
      <center>
      <h2>CSU Chico</h2>
      <img src="media/images/chico.jpg" class="thumbnail" />
      <p>Graduated with my BS in Computer Science and minor in Mathematics from CSU Chico </p>
      <p><a class="btn" href="chico.html">View details &raquo;</a></p>
      </center>
    </div>
    <!--
      <div class="span4">
      <center>
      <h2>Internet</h2>
      <img src="media/images/social.jpg" class="thumbnail" />
      <p>Currently in love with social media and the idea of "<i>self brand</i>"</p>
      <p><a class="btn" href="social.html">View details &raquo;</a></p>
      </center>
    </div>
  -->
  </div>
</div>
