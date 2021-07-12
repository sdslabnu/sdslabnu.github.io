---
title: "SDS Lab - Pictures"
layout: piclay
excerpt: "SDS Lab -- Pictures"
permalink: /pictures/
---

# Dialouge of Civilizations 
The SDS Lab has been organizing, each summer, undergraduate study abroad programs in climate change science, engineering adaptation, and policy, covering different parts of the world with a focus on emerging economies. The programs are organized as part of Northeastern University's Dialogue of Civilizations and led by the SDS Lab PI who serves as the primary instructor. A feature of these programs are climate change war games where students engage in informed role-playing. In addition to the participating undergraduate students, past programs have included SDS Lab PhD students as co-instructors and SDS Lab undergraduate researchers as student mentors. Over the years, this interdisciplinary program has enrolled undergraduate students from all colleges at Northeastern, and traveled to Brazil, India, Indonesia, Nepal, Peru, and Singapore.  

<br>

| <b><a href='https://web.northeastern.edu/sds/ClimateDOC/summer_2014_India.html'>2014 program</a></b><img src='/images/respic/Dialogue_2014_Poster.jpg' class='img-responsive' style='max-width: 250px' /> | <b><a href='https://web.northeastern.edu/sds/ClimateDOC/summer_2015_India.html'>2015 program</a></b><img src='/images/respic/Dialogue_2015_Poster.jpg' class='img-responsive' style='max-width: 250px' /> | <b><a href='https://news.northeastern.edu/2015/07/17/the-impact-of-climate-change-beyond-the-weather/'>2015</a></b><img src='/images/respic/2015.jpg' class='img-responsive' style='max-width: 250px' />|
| :------------- |:-------------| :-----------|
| <b><a href='https://cee.northeastern.edu/news/studying-climate-change-in-india/'>2016</a></b><img src='/images/respic/2016_DIALOUGE.jpg' class='img-responsive' style='max-width: 250px' /> | <b><a href='Studying the Science and Politics of Climate Change in Singapore, Jakarta, and Bali'>2017</a></b><img src='/images/respic/2017 Sin_bali.jpg' class='img-responsive' style='max-width: 250px' /> | <b><a href='https://coe.northeastern.edu/news/climate-dialogue-to-peru-brazil-completes-2-of-4-phases/'>2018(Phase I-II)</a></b><img src='/images/respic/2018-brazil-peru.jpg' class='img-responsive' style='max-width: 250px' /> |
| <b><a href='https://coe.northeastern.edu/news/climate-dialogue-to-peru-brazil-completes-last-two-phases/'>2018(Phase III-IV)</a></b><img src='/images/respic/2018 Phase34.jpg' class='img-responsive' style='max-width: 250px' /> | <b><a href='https://coe.northeastern.edu/news/studying-climate-change-in-india-2/'>2019</a></b><img src='/images/respic/2019.jpg' class='img-responsive' style='max-width: 250px' />| <b><a href='https://violetlingenfelter.com/projects/dialogue-website/about/'>2019</a></b><img src='/images/respic/2019_2.webp' class='img-responsive' style='max-width: 250px' />|
| <b><a href='https://cee.northeastern.edu/news/the-2020-virtual-dialogue-of-civilizations-program-on-climate-change-science-and-policy/'>2020 Virtual</a></b><img src='/images/respic/2020.png' class='img-responsive' style='max-width: 250px' /> |  |  |



<hr>
 
<!--- <a href='https://web.northeastern.edu/sds/ClimateDOC/summer_2014_India.html'>2014 program</a><br />
<a href='https://web.northeastern.edu/sds/ClimateDOC/summer_2015_India.html'>2015 program</a><br />
<a href='https://news.northeastern.edu/2015/07/17/the-impact-of-climate-change-beyond-the-weather/'>2015</a><br />
<a href='http://www.civ.neu.edu/news/studying-climate-change-india'>2016</a><br />
<a href='http://www.coe.neu.edu/blog/studying-science-and-politics-climate-change-singapore-jakarta-bali'>2017</a><br />
<a href='http://www.civ.neu.edu/news/climate-dialogue-peru-brazil-completes-2-4-phases'>2018</a><br />
<a href='http://www.civ.neu.edu/news/climate-dialogue-peru-brazil-completes-last-two-phases'>2018</a><br />
<a href='https://coe.northeastern.edu/news/studying-climate-change-in-india-2/'>2019</a><br />
<a href='https://violetlingenfelter.com/projects/dialogue-website/about/'>2019</a><br />
<a href='https://cee.northeastern.edu/news/the-2020-virtual-dialogue-of-civilizations-program-on-climate-change-science-and-policy/'>2020</a><br />
--> 

### <a href='https://www.nature.com/articles/454673a'>The CNAS climate wargames which originally motivated the Dialogue wargames</a><br />

<hr>

# Gallery
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




