---
title: "News"
layout: textlay
excerpt: "AequitasLAB at ECTI-UNAD."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
