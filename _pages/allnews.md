---
title: "News"
layout: textlay
excerpt: "LEAPH at Dalhousie University"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }}  
<li> {{ article.headline | markdownify}}
{% endfor %}
