---
title: "News"
layout: textlay
excerpt: "UTS NLP"
sitemap: false
permalink: /allnews.html
---

# News

<ul>
{%- for article in site.data.news -%}
<li>
<p><b>[{{- article.date -}}]</b> &nbsp; {{- article.headline | markdownify | remove: '<p>' | remove: '</p>' -}}</p>
</li>
{%- endfor -%}
</ul>

<br>