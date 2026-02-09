---
title: "News"
layout: textlay
excerpt: "SDS Lab at Northeastern University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p style="text-align: justify;"><span style="color: #c8102e;">{{ article.date }}</span> <br>
{{ article.headline }}</p>
{% endfor %}
