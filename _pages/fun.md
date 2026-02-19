---
title: "SDS Lab"
layout: textlay
excerpt: "Fun parts of the Lab"
sitemap: false
permalink: /fun/
---

<hr>

## Gallery

<hr>

<div class="fun-gallery">
{% for pic in site.data.pictures_Leiden reversed %}
{% assign index = forloop.index0 %}
{% assign mod = index | modulo: 4 %}
{% if mod == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6 col-md-3 fun-grid-item">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" alt="{{ pic.title }}" />
</div>
{% if mod == 3 or forloop.last %}
</div>
{% endif %}
{% endfor %}
</div>

<p> &nbsp; </p>
