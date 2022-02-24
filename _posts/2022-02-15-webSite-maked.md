---
layout: post
title: "My site that's actually being used."
categories: [Design]
image: assets/images/demo1.jpg
---

<p class="text-dark text-left">실제로 회사에서 사용된 저의 홈페이지 작업물들 입니다.</p>


<div class="row justify-content-center">
  <div class="col-md-8">
      <div class="row">
          <a href="https://unsplash.it/1200/768.jpg?image=251" data-toggle="lightbox" data-gallery="example-gallery" class="col-sm-4">
              <img src="https://unsplash.it/600.jpg?image=251" class="img-fluid">
          </a>
          <a href="https://unsplash.it/1200/768.jpg?image=252" data-toggle="lightbox" data-gallery="example-gallery" class="col-sm-4">
              <img src="https://unsplash.it/600.jpg?image=252" class="img-fluid">
          </a>
          <a href="https://unsplash.it/1200/768.jpg?image=253" data-toggle="lightbox" data-gallery="example-gallery" class="col-sm-4">
              <img src="https://unsplash.it/600.jpg?image=253" class="img-fluid">
          </a>
      </div>
      <div class="row">
          <a href="https://unsplash.it/1200/768.jpg?image=254" data-toggle="lightbox" data-gallery="example-gallery" class="col-sm-4">
              <img src="https://unsplash.it/600.jpg?image=254" class="img-fluid">
          </a>
          <a href="https://unsplash.it/1200/768.jpg?image=255" data-toggle="lightbox" data-gallery="example-gallery" class="col-sm-4">
              <img src="https://unsplash.it/600.jpg?image=255" class="img-fluid">
          </a>
          <a href="https://unsplash.it/1200/768.jpg?image=256" data-toggle="lightbox" data-gallery="example-gallery" class="col-sm-4">
              <img src="https://unsplash.it/600.jpg?image=256" class="img-fluid">
          </a>
      </div>
  </div>
</div>


<script>

$(document).on('click', '[data-toggle="lightbox"]', function(event) {
                event.preventDefault();
                $(this).ekkoLightbox();
            });


</script>