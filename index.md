---
layout: archive
permalink: /
title: "IGSA"
---

<style>
.parallax {
  /* The image used */
  background-image: url("https://IGSA-SICCS.github.io/images/sev.jpg");

  /* Set a specific height */
  height: 200px;

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>

<!-- Container element -->
<div class="parallax"></div>


<p> IGSA is an organization of SICCS graduate students who aim to (1) promote participation from graduate students in the School of Informatics, Computing, & Cyber Systems (SICCS) in the form of scientific outreach, workshops, and community building, (2) advocate for SICCS graduate student rights and create an environment of outreach, support, and inclusion, (3) provide leadership in developing, implementing, and organizing events and activities that are designed to increase awareness of pathways to success in science and encourage broad participation in science, and (4) foster a space for community building and camaraderie among graduate students in SICCS.</p>


<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
