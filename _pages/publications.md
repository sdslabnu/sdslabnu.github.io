---
title: "SDS Lab - Publications"
layout: gridlay
excerpt: "SDS Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications


<!--(For a full list see [below](#full-list) or go to [Google Scholar](https://scholar.google.ch/citations?user=TqxYWZsAAAAJ), [ResearcherID](https://www.researcherid.com/rid/D-7763-2012)) !-->

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-12 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <a href="{{ publi.link.url }}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  </a>
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="10000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
        <li data-target="#carousel" data-slide-to="5"></li>
        <li data-target="#carousel" data-slide-to="6"></li>
        <li data-target="#carousel" data-slide-to="7"></li>
        <li data-target="#carousel" data-slide-to="8"></li>
        <li data-target="#carousel" data-slide-to="9"></li>
        <li data-target="#carousel" data-slide-to="10"></li>
        <li data-target="#carousel" data-slide-to="11"></li>
        <li data-target="#carousel" data-slide-to="12"></li>
        <li data-target="#carousel" data-slide-to="13"></li>
        <li data-target="#carousel" data-slide-to="14"></li>
        <li data-target="#carousel" data-slide-to="15"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">

        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-1.png" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-2.png" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-3.png" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-4.png" alt="Slide 4" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-5.png" alt="Slide 5" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-6.png" alt="Slide 6" />
        </div>       
         <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-7.png" alt="Slide 7" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-8.png" alt="Slide 8" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-9.png" alt="Slide 9" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-10.png" alt="Slide 10" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-11.png" alt="Slide 11" />
        </div>       
         <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-12.png" alt="Slide 12" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-13.png" alt="Slide 13" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-14.png" alt="Slide 14" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-15.png" alt="Slide 15" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SDS Website Slides Compact-16.png" alt="Slide 16" />
        </div>
    </div>
  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

## Selected Publications and Links


* Slide 1 :
  * 1st Paper :
* Slide 2 :
  * 1st Paper : <a href='https://doi.org/10.1073/pnas.0904495106'>DOI</a>
  * 2nd Paper :
* Slide 3 :
* Slide 4 :
* Slide 5 :
* Slide 6 :
* Slide 7 :
* Slide 8 :
* Slide 9 :
* Slide 10 :
* Slide 11 :
* Slide 12 :
* Slide 13 :
* Slide 14 :
* Slide 15 :

For a full list of publications, visit the PI's Google Scholar page <a href='https://scholar.google.com/citations?user=eNrAUJMAAAAJ&hl=en'>here</a>.
