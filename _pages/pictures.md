---
title: "SDS Lab - Pictures"
layout: piclay
excerpt: "SDS Lab -- Pictures"
permalink: /pictures/
---

# Dialouge of Civilization : 
SDS Lab has been organizing an undergraduate study abroad program in climate change science, engineering and policy in different parts of the world. Besides, the undergraduate students program involves PI along with PhD students as co-instructor.



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






{% for product in site.data.pictures_Leiden %}
  {% assign evens = forloop.index | modulo: 2 %}
  {% if evens == 0 %}
    <!-- even layout html -->
<div class="box-product-whole-container that-goes-opposite">
      {% if product.description != blank %}
         <div class="description title-for-bp-page" itemprop="description">
           {{ product.description | split: '<!-- split -->' | first }}
      	</div>
       {% endif %}
  		<div class="box-small-image-container">
			<div class="divBSsquare">
              <img src="{{ product.images[1] | img_url: '275x205' }}" alt="{{ product.image.alt }}"/>
			</div>
        	<div class="divBSsquare">
              <img src="{{ product.images[2] | img_url: '275x205' }}" alt="{{ product.image.alt }}"/>
			</div>
        	<div class="box-clear" style="clear:both"></div>
        	<div class="divBSsquare">
              <img src="{{ product.images[3] | img_url: '275x205' }}" alt="{{ product.image.alt }}"/>
			</div>
        	<div class="divBSsquare">
              <img src="{{ product.images[4] | img_url: '275x205' }}" alt="{{ product.image.alt }}"/>
			</div>
      </div>
      <div class="box-big-image-container">
      	<img class="box-big-image" src="{{ product.featured_image | img_url: '550x415'}}"/>
        <div class="box-la-description">
          <div class="box-la-descri-names">	
          		<div class="box-la-collection-name">
          			{{ collection.title }}
          		</div>
          		<div class="box-la-vendor-name">
          			{{ product.vendor }}
          		</div>
          		<div class="box-la-product-name">
          			{{ product.title }}
          		</div>
          </div>
          <div class="box-la-button-container">
            <a href="{{ product.url }}">ACHETER</a>
            <!--<a href="https://www.laboxhomme.com/collections/box-precedentes">DÉCOUVRIR</a>-->
          </div>
        </div>
      </div>
    </div>
  {% else %}
    <!-- odd layout html -->
<div class="box-product-whole-container that-goes-left">
      {% if product.description != blank %}
         <div class="description title-for-bp-page" itemprop="description">
           {{ product.description | split: '<!-- split -->' | first }}
      	</div>
       {% endif %}
      <div class="box-big-image-container">
      	<img class="box-big-image" src="{{ product.featured_image | img_url: '550x415'}}"/>
        <div class="box-la-description">
          <div class="box-la-descri-names">	
          		<div class="box-la-collection-name">
          			{{ collection.title }}
          		</div>
          		<div class="box-la-vendor-name">
          			{{ product.vendor }}
          		</div>
          		<div class="box-la-product-name">
          			{{ product.title }}
          		</div>
          </div>
          <div class="box-la-button-container">
            <a href="{{ product.url }}">ACHETER</a>
            <!--<a href="https://www.laboxhomme.com/collections/box-precedentes">DÉCOUVRIR</a>-->
          </div>
        </div>
      </div>
      <div class="box-small-image-container">
			<div class="divBSsquare">
              <img src="{{ product.images[1] | img_url: '275x205' }}" alt="{{ product.image.alt }}"/>
			</div>
        	<div class="divBSsquare">
              <img src="{{ product.images[2] | img_url: '275x205' }}" alt="{{ product.image.alt }}"/>
			</div>
        	<div class="box-clear" style="clear:both"></div>
        	<div class="divBSsquare">
              <img src="{{ product.images[3] | img_url: '275x205' }}" alt="{{ product.image.alt }}"/>
			</div>
        	<div class="divBSsquare">
              <img src="{{ product.images[4] | img_url: '275x205' }}" alt="{{ product.image.alt }}"/>
			</div>
      </div>
    </div>
  {% endif %}
{% endfor %}


