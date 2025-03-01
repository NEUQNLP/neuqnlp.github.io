---
title: "NEUQ LIS - Team"
layout: gridlay
excerpt: "NEUQ LIS: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are  looking for new undergraduate students to join the team** **!**


<!-- Jump to [faculty](#faculty), [PhD students](#phd-students), [master students](#master-(research)-students), [alumni](#alumni). -->
 <!-- [administrative support](#administrative-support), [lab visitors](#lab-visitors). -->



<br>

## Faculty 
{% assign number_printed = 0 %}
{% for member in site.data.faculty_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="avatar_img"  style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>
    since {{ member.duration }} 
    <!-- <br>
    co-supervised with {{ member.cosupervision }} -->
  </i>
  <br>
  {% if member.url.personal_site != nil %}
  <a href="{{ member.url.personal_site }}" target="_blank"><i class="fa-solid fa-house"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.google_scholar != nil %}
  <a href="{{ member.url.google_scholar }}" target="_blank"><i class="fa-brands fa-google"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.github != nil %}
  <a href="{{ member.url.github }}" target="_blank"><i class="fa-brands fa-github"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.linkedin != nil %}
  <a href="{{ member.url.linkedin }}" target="_blank"><i class="fa-brands fa-linkedin"></i></a> &nbsp;
  {%- endif -%}
  <!-- <i class="fa fa-envelope"></i> -->
  <!-- <ul style="overflow: hidden">
  </ul> -->

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<br>


##  Laboratory Student Leaders
{% assign number_printed = 0 %}
{% for member in site.data.student_manager %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="avatar_img"  style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>
    since {{ member.duration }} 
    <!-- co-supervised with {{ member.cosupervision }} -->
  </i>
  <br>
  {% if member.url.personal_site != nil %}
  <a href="{{ member.url.personal_site }}" target="_blank"><i class="fa-solid fa-house"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.google_scholar != nil %}
  <a href="{{ member.url.google_scholar }}" target="_blank"><i class="fa-brands fa-google"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.github != nil %}
  <a href="{{ member.url.github }}" target="_blank"><i class="fa-brands fa-github"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.linkedin != nil %}
  <a href="{{ member.url.linkedin }}" target="_blank"><i class="fa-brands fa-linkedin"></i></a> &nbsp;
  {%- endif -%}
  <!-- <ul style="overflow: hidden">
  </ul> -->

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<br>






## Bachelor  Students
{% assign number_printed = 0 %}
{% for member in site.data.bachelor_students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="avatar_img"  style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>
    {{ member.duration }} 
    <br>
  <span style="color: red;">{{ member.info }}</span>
  </i>
  <br>
  {% if member.url.personal_site != nil %}
  <a href="{{ member.url.personal_site }}" target="_blank"><i class="fa-solid fa-house"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.google_scholar != nil %}
  <a href="{{ member.url.google_scholar }}" target="_blank"><i class="fa-brands fa-google"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.github != nil %}
  <a href="{{ member.url.github }}" target="_blank"><i class="fa-brands fa-github"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.linkedin != nil %}
  <a href="{{ member.url.linkedin }}" target="_blank"><i class="fa-brands fa-linkedin"></i></a> &nbsp;
  {%- endif -%}
  <!-- <ul style="overflow: hidden">
  </ul> -->

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<br>

## Alumni

{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="avatar_img"  style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>
    {{ member.duration }} 
    <br>
    <!-- co-supervised with {{ member.cosupervision }}
    <br>  -->
    Current: {{ member.info }}
  </i>
  <br>
  {% if member.url.personal_site != nil %}
  <a href="{{ member.url.personal_site }}" target="_blank"><i class="fa-solid fa-house"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.google_scholar != nil %}
  <a href="{{ member.url.google_scholar }}" target="_blank"><i class="fa-brands fa-google"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.github != nil %}
  <a href="{{ member.url.github }}" target="_blank"><i class="fa-brands fa-github"></i></a> &nbsp;
  {%- endif -%}
  {% if member.url.linkedin != nil %}
  <a href="{{ member.url.linkedin }}" target="_blank"><i class="fa-brands fa-linkedin"></i></a> &nbsp;
  {%- endif -%}
  <!-- <ul style="overflow: hidden">
  </ul> -->
  
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<!-- ## Former visitors, BSc/ MSc students
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

</div> -->

<br>

<!-- ## Administrative Support
<a href="mailto:Rijsewijk@Physics.LeidenUniv.nl">Ellie van Rijsewijk</a> is helping us (and other groups) with administration. -->
