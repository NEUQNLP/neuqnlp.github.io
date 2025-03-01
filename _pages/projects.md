---
title: "UTS NLP - Projects"
layout: textlay
excerpt: "Projects"
sitemap: false
permalink: /projects
---

# Projects

{% for project in site.data.projects %}

  <div class="col-sm-6 clearfix">
  <div class="well">
  **{{ project.title }}**
  <img src="{{ site.url }}{{ site.baseurl }}/images/projects/{{ project.image }}" class="project_img"  style="float: left" />
  <p>{{ project.description }}</p>
  <!-- <p><em>{{ project.authors }}</em></p> -->
  <!-- **[Code]({{ project.code }}){:target="_blank"}**, -->
  <a href="{{ project.code }}" target="_blank"><i class="fa-brands fa-github"></i></a>, &nbsp;
  **[Read More]({{ project.page }}){:target="_blank"}**
  </div>
  </div>


{% endfor %}


<p> &nbsp; </p>

<br>