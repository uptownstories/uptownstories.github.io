---
layout: page
title: Classes
permalink: /classes/
---

<div class="row">
  <div class="col-sm-8 col-sm-offset-2">
    {% for class in site.classes %}
      {% include class.html class=class %}
    {% endfor %}
  </div>  
</div>
