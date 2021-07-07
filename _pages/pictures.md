---
title: "SDS Lab - Pictures"
layout: piclay
excerpt: "SDS Lab -- Pictures"
permalink: /pictures/
---

# Dialouge of Civilization : 
SDS Lab has been organizing an undergraduate study abroad program in climate change science, engineering and policy in different parts of the world. Besides, the undergraduate students program involves PI along with PhD students as co-instructor.

<br>

| <b><a href='https://www.nature.com/articles/s41586-019-1408-8'>2014 program</a>!</b><img src='/images/respic/Layer_1.PNG' class='img-responsive' style='max-width: 192px' /> | 2015 program | 2015|
| :------------- |:-------------| :-----------|
| [2016](https://web.northeastern.edu/sds/ClimateDOC/summer_2014_India.html) | 2017 | 2018 |
| [2018](https://web.northeastern.edu/sds/ClimateDOC/summer_2014_India.html) | 2019 | [2019](https://web.northeastern.edu/sds/ClimateDOC/summer_2014_India.html)|



<hr>

<a href='https://web.northeastern.edu/sds/ClimateDOC/summer_2014_India.html'>2014 program</a><br />
<a href='https://web.northeastern.edu/sds/ClimateDOC/summer_2015_India.html'>2015 program</a><br />
<a href='https://news.northeastern.edu/2015/07/17/the-impact-of-climate-change-beyond-the-weather/'>2015</a><br />
<a href='http://www.civ.neu.edu/news/studying-climate-change-india'>2016</a><br />
<a href='http://www.coe.neu.edu/blog/studying-science-and-politics-climate-change-singapore-jakarta-bali'>2017</a><br />
<a href='http://www.civ.neu.edu/news/climate-dialogue-peru-brazil-completes-2-4-phases'>2018</a><br />
<a href='http://www.civ.neu.edu/news/climate-dialogue-peru-brazil-completes-last-two-phases'>2018</a><br />
<a href='https://coe.northeastern.edu/news/studying-climate-change-in-india-2/'>2019</a><br />
<a href='https://violetlingenfelter.com/projects/dialogue-website/about/'>2019</a><br />
<a href='https://cee.northeastern.edu/news/the-2020-virtual-dialogue-of-civilizations-program-on-climate-change-science-and-policy/'>2020</a><br />

<a href='https://www.nature.com/articles/454673a'>The CNAS climate wargames which originally motivated the Dialogue wargames</a><br />

<hr>

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




