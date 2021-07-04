---
title: "SDS Lab - Pictures"
layout: piclay
excerpt: "SDS Lab -- Pictures"
permalink: /pictures/
---

# Pictures
Jump to: [NEU](#ethz), [SDS](#cornell), [Climate Talk](#st-andrews)



##### risQ: A Northeastern University SDS Lab Climate Spinout:

<iframe width="500" height="282" src="https://www.youtube.com/embed/Eq4JDHhVno4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

##### Keynotes: The National Academy
<iframe title="vimeo-player" src="https://player.vimeo.com/video/318854857" width="500" height="282" frameborder="0" allowfullscreen></iframe>

##### SERDP 2020-Symposium: Project NICE by Auroop Ganguly
<iframe width="500" height="282" src="https://www.youtube.com/embed/BRsifIgUdHA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


#### Gallery
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>

## Climate Dialouge
From the [group of Andreas Wallraff](http://www.qudev.ethz.ch/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageETH_red.jpg" width="60%">
</figure>

## Cornell
From the [group of Seamus JC Davis](http://davisgroup.lassp.cornell.edu).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageCornell_red.jpg" width="60%">
</figure>

