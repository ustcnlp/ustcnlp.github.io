---
title: "USTC NLP Group - Publications"
layout: gridlay
excerpt: "USTC NLP Group - Publications."
sitemap: false
permalink: /publications/
---


# Publications

{% for publi in site.data.publist %}

- **{{ publi.title }}** <br />
  <em>{{ publi.authors }} </em><br />
  <em>{{ publi.venue }} </em><br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
