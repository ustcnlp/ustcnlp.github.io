---
title: "USTC NLP Group - News"
layout: textlay
excerpt: "USTC NLP Group: News"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
