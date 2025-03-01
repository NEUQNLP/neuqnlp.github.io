---
title: "UTS NLP - Publications"
layout: gridlay
excerpt: "UTS NLP -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## 2025
---

{% for publi in site.data.publist %}

  {% if publi.year == 2025 %}

  **{{ publi.title }}** <br />
  <em>{{ publi.authors }} </em>
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
  <em>{{ publi.authors }} </em>
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

## 2023
---

{% for publi in site.data.publist %}

  {% if publi.year == 2023 %}

  **{{ publi.title }}** <br />
  <em>{{ publi.authors }} </em>
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

## 2022
---

{% for publi in site.data.publist %}

  {% if publi.year == 2022 %}

  **{{ publi.title }}** <br />
  <em>{{ publi.authors }} </em>
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

## 2021
---

{% for publi in site.data.publist %}

  {% if publi.year == 2021 %}

  **{{ publi.title }}** <br />
  <em>{{ publi.authors }} </em>
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

## 2020
---

{% for publi in site.data.publist %}

  {% if publi.year == 2020 %}

  **{{ publi.title }}** <br />
  <em>{{ publi.authors }} </em>
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
