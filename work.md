---
layout: default
title: Works
permalink: /works/
---


<div class="container">
  <div class="row">
  {% for work in site.works %}
    <div class="col-md-4 col-xs-6">
      <a href="{{ work.url }}">
        <div class="thumbnail">
          <img src="/img/{{ work.icon }}" alt="...">
          <div class="caption"><h4>{{ work.title }}</h4></div>
        </div>
      </a> 
    </div>
  {% endfor %}
  </div>
</div>
