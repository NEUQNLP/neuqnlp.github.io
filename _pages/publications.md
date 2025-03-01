---
title: "NEUQ LIS - Publications"
layout: gridlay
excerpt: "NEUQ LIS -- Publications."
sitemap: false
permalink: /publications/
---


# Publications
<span style="color: red;">All publications was done during the students study in NEUQ LIS.</span>
<br>
<b>Bolded text</b> represents students in this lab

## 2025
---

{% for publi in site.data.publist %}

  {% if publi.year == 2025 %}

  **{{ publi.title }}** <br />
  {{ publi.authors }}
  <br />
  in <ins>***{{ publi.venue }}***</ins>, &nbsp;
  <!-- [Paper]({{ publi.link.url }}){:target="_blank"},  -->
  {%- if publi.link.url != nil -%}
  <a href="{{ publi.link.url }}" target="_blank"><i class="fa-regular fa-file-pdf"></i></a> &nbsp;
  {%- endif -%}

  {%- if publi.link.code == nil -%}
  <!-- (Code coming soon) -->
  {%- else -%}
  <!-- [Code]({{ publi.link.code }}){:target="_blank"} -->
  <a href="{{ publi.link.code }}" target="_blank"><i class="fa-brands fa-github"></i></a> &nbsp;
  {%- endif -%}

  {% endif %}

{% endfor %}

<br>



## 2024
---

{% for publi in site.data.publist %}

  {% if publi.year == 2024 %}

  **{{ publi.title }}** <br />
  {{ publi.authors }}
  <br />
  in <ins>***{{ publi.venue }}***</ins>, &nbsp;
  <!-- [Paper]({{ publi.link.url }}){:target="_blank"},  -->
  {%- if publi.link.url != nil -%}
  <a href="{{ publi.link.url }}" target="_blank"><i class="fa-regular fa-file-pdf"></i></a> &nbsp;
  {%- endif -%}

  {%- if publi.link.code == nil -%}
  <!-- (Code coming soon) -->
  {%- else -%}
  <!-- [Code]({{ publi.link.code }}){:target="_blank"} -->
  <a href="{{ publi.link.code }}" target="_blank"><i class="fa-brands fa-github"></i></a> &nbsp;
  {%- endif -%}

  {% endif %}

{% endfor %}

<br>