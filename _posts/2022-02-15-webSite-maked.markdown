---
layout: post
title:  "My site that's actually being used."
categories: [ Design ]
image: assets/images/demo1.jpg
---

<p>실제로 회사에서 사용된 저의 홈페이지 작업물들 입니다.</p>



<div class="container">
 <div class="row col-12 h-max-100 flex-wrap flex-raw ">
            {% assign posts = site.posts | where:"author","master" %}
            {% for post in posts02 %}
            {% include main-loop-card.html %}
            {% endfor %}

        </div>
</div>