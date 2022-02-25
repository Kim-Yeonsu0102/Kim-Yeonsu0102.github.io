---
layout: post
title: "My site Design"
categories: [Design]
image: assets/images/demo1.jpg
---


<p class="text-dark text-left">실제로 회사에서 사용된 저의 홈페이지 작업물들 입니다.</p>
<p class="text-dark text-left">호스팅이 끊긴 곳이 많아서 캡쳐로 대신합니다.</p>

 <link rel="stylesheet" href="\bower_components\magnific-popup\dist\magnific-popup.css">



<div class="row flex-row flex-wrap">
<ul class="col12 d-flex flex-wrap siteUl">

<li class="col-6 col-md-4">
<a id="open-popup01" class="d-flex flex-column text-center image-link gallery-item mfp-image no-gutters" href="/assets/images/siteImade/01/01_01.png">
<img src="/assets/images/siteImade/01/01_01.png" />
</a>

<span class="d-block mt-2 text-purple col-12 font-weight-bold text-center">거성닥트</span>
</li>


<li class="col-6 col-md-4 ">
<a id="open-popup02" class="d-flex flex-column text-center image-link gallery-item mfp-image no-gutters" href="/assets/images/siteImade/02/02_01.png">
<img src="/assets/images/siteImade/02/02_01.png" />
</a>

<span class="d-block mt-2 text-purple col-12 font-weight-bold text-center">길심리발달센터</span>
</li>


<!-- <li class="col-6 col-md-4">
<a id="open-popup03" class="d-flex flex-column text-center image-link gallery-item mfp-image no-gutters" href="/assets/images/siteImade/03/03_01.png">
<img src="/assets/images/siteImade/03/03_01.png" />
</a>

<span class="d-block mt-2 text-purple col-12 font-weight-bold text-center">대륜건설</span>
</li> -->

<li class="col-6 col-md-4">
<a id="open-popup04" class="d-flex flex-column text-center image-link gallery-item mfp-image no-gutters" href="/assets/images/siteImade/04/04_01.png">
<img src="/assets/images/siteImade/04/04_01.png" />
</a>
<span class="d-block mt-2 text-purple col-12 font-weight-bold text-center">보령전통식품</span>
</li>


<li class="col-6 col-md-4">
<a id="open-popup05" class="d-flex flex-column text-center image-link gallery-item mfp-image no-gutters" href="/assets/images/siteImade/05/05_01.png">
<img src="/assets/images/siteImade/05/05_01.png" />
</a>

<span class="d-block mt-2 text-purple col-12 font-weight-bold text-center">비전창호</span>
</li>

<li class="col-6 col-md-4">
<a id="open-popup06" class="d-flex flex-column text-center image-link gallery-item mfp-image no-gutters" href="/assets/images/siteImade/06/06_01.png">
<img src="/assets/images/siteImade/06/06_01.png" />
</a>

<span class="d-block mt-2 text-purple col-12 font-weight-bold text-center">솔담디자인</span>
</li>

<li class="col-6 col-md-4">
<a id="open-popup07" class="d-flex flex-column text-center image-link gallery-item mfp-image no-gutters" href="/assets/images/siteImade/07/07_01.png">
<img src="/assets/images/siteImade/07/07_01.png" />
</a>

<span class="d-block mt-2 text-purple col-12 font-weight-bold text-center">영광손해사정</span>
</li>

<li class="col-6 col-md-4">
<a id="open-popup08" class="d-flex flex-column text-center image-link gallery-item mfp-image no-gutters" href="/assets/images/siteImade/08/08_01.png">
<img src="/assets/images/siteImade/08/08_01.png" />
</a>
<span class="d-block mt-2 text-purple col-12 font-weight-bold text-center">토탈지게차서비스</span>

</li>


<li class="col-6 col-md-4">
<a id="open-popup09" class="d-flex flex-column text-center image-link gallery-item mfp-image no-gutters" href="/assets/images/siteImade/09/09_01.png">
<img src="/assets/images/siteImade/09/09_01.png" />
</a>

<span class="d-block mt-2 text-purple col-12 font-weight-bold text-center">학원시안</span>
</li>


<li class="col-6 col-md-4">
<a id="open-popup10" class="d-flex flex-column text-center image-link gallery-item mfp-image no-gutters" href="/assets/images/siteImade/10/10_01.png">
<img src="/assets/images/siteImade/10/10_01.png" />
</a>

<span class="d-block mt-2 text-purple col-12 font-weight-bold text-center">회산</span>
</li>
</ul>

</div>

<script src="\bower_components\magnific-popup\dist\jquery.magnific-popup.js"></script>

<script>
$(document).ready(function() {
  $('#open-popup01').magnificPopup({
    items: [
      {
        src: '/assets/images/siteImade/01/01_01.png',
        title: '거성닥트',
      },     
      {
        src: '/assets/images/siteImade/01/01_02.png',
        title: '거성닥트',
      
      } 
    ],    
  type: 'image',
       closeOnContentClick: true,
       closeBtnInside: true,
       fixedContentPos: true,
    gallery: { 
            enabled: true,
            preload: [0,2],
            navigateByImgClick: true,
              tPrev: 'Previous (Left arrow key)', // title for left button
  tNext: 'Next (Right arrow key)', // title for right button
  tCounter: '<span class="mfp-counter">%curr% of %total%</span>' 
  }, 
       image: { verticalFit: false ,
       cursor: 'mfp-zoom-out-cur',},
      
       zoom: {enabled: true,   duration: 500 ,easing: 'ease-in-out' }
 });

  $('#open-popup02').magnificPopup({
    items: [
      {
        src: '/assets/images/siteImade/02/02_01.png',
        title: '길심리발달센터',
      },     
      {
        src: '/assets/images/siteImade/02/02_02.png',
        title: '길심리발달센터',
      },     
      {
        src: '/assets/images/siteImade/02/02_03.png',
        title: '길심리발달센터',
      },     
      {
        src: '/assets/images/siteImade/02/02_04.png',
        title: '길심리발달센터',
      }   
    
    ],    
  type: 'image',
       closeOnContentClick: true,
       closeBtnInside: true,
       fixedContentPos: true,
    gallery: { 
            enabled: true,
            preload: [0,2],
            navigateByImgClick: true,

              tPrev: 'Previous (Left arrow key)', // title for left button
  tNext: 'Next (Right arrow key)', // title for right button
  tCounter: '<span class="mfp-counter">%curr% of %total%</span>' 
            
  }, 
       image: {  verticalFit: false ,
       cursor: 'mfp-zoom-out-cur',},
      
       zoom: {enabled: true,   duration: 500 ,easing: 'ease-in-out' }


 }); 


$('#open-popup03').magnificPopup({
    items: [
      {
        src: '/assets/images/siteImade/03/03_01.png',
        title: '대륜건설',
      },     
      {
        src: '/assets/images/siteImade/03/03_02.png',
        title: '대륜건설',
      },     
      
    
    ],    
  type: 'image',
       closeOnContentClick: true,
       closeBtnInside: true,
       fixedContentPos: true,
    gallery: { 
            enabled: true,
            preload: [0,2],
            navigateByImgClick: true,

              tPrev: 'Previous (Left arrow key)', // title for left button
  tNext: 'Next (Right arrow key)', // title for right button
  tCounter: '<span class="mfp-counter">%curr% of %total%</span>' 
            
  }, 
       image: {  verticalFit: false ,
       cursor: 'mfp-zoom-out-cur',},
      
       zoom: {enabled: true,   duration: 500 ,easing: 'ease-in-out' }


 });


  $('#open-popup04').magnificPopup({
    items: [
      {
        src: '/assets/images/siteImade/04/04_01.png',
        title: '보령전통식품',
      },     
      {
        src: '/assets/images/siteImade/04/04_02.png',
        title: '보령전통식품',
      },     
      {
        src: '/assets/images/siteImade/04/04_03.png',
        title: '보령전통식품',
      },     
      {
        src: '/assets/images/siteImade/04/04_04.png',
        title: '보령전통식품',
      }   
    
    ],    
  type: 'image',
       closeOnContentClick: true,
       closeBtnInside: true,
       fixedContentPos: true,
    gallery: { 
            enabled: true,
            preload: [0,2],
            navigateByImgClick: true,

              tPrev: 'Previous (Left arrow key)', // title for left button
  tNext: 'Next (Right arrow key)', // title for right button
  tCounter: '<span class="mfp-counter">%curr% of %total%</span>' 
            
  }, 
       image: {  verticalFit: false ,
       cursor: 'mfp-zoom-out-cur',},
      
       zoom: {enabled: true,   duration: 500 ,easing: 'ease-in-out' }


 }); 


 $('#open-popup05').magnificPopup({
    items: [
      {
        src: '/assets/images/siteImade/05/05_01.png',
        title: '비전창호',
      },     
      {
        src: '/assets/images/siteImade/05/05_02.png',
        title: '비전창호',
      },     
      {
        src: '/assets/images/siteImade/05/05_03.png',
        title: '비전창호',
      },     
      {
        src: '/assets/images/siteImade/05/05_04.png',
        title: '비전창호',
      },     
      {
        src: '/assets/images/siteImade/05/05_05.png',
        title: '비전창호',
      }      
    
    ],    
  type: 'image',
       closeOnContentClick: true,
       closeBtnInside: true,
       fixedContentPos: true,
    gallery: { 
            enabled: true,
            preload: [0,2],
            navigateByImgClick: true,

              tPrev: 'Previous (Left arrow key)', // title for left button
  tNext: 'Next (Right arrow key)', // title for right button
  tCounter: '<span class="mfp-counter">%curr% of %total%</span>' 
            
  }, 
       image: {  verticalFit: false ,
       cursor: 'mfp-zoom-out-cur',},
      
       zoom: {enabled: true,   duration: 500 ,easing: 'ease-in-out' }


 }); 



 $('#open-popup06').magnificPopup({
    items: [
      {
        src: '/assets/images/siteImade/06/06_01.png',
        title: '솔담디자인',
      },     
      {
        src: '/assets/images/siteImade/06/06_02.png',
        title: '솔담디자인',
      },     
      {
        src: '/assets/images/siteImade/06/06_03.png',
        title: '솔담디자인',
      },     
      {
        src: '/assets/images/siteImade/06/06_04.png',
        title: '솔담디자인',
      }     
          
    
    ],    
  type: 'image',
       closeOnContentClick: true,
       closeBtnInside: true,
       fixedContentPos: true,
    gallery: { 
            enabled: true,
            preload: [0,2],
            navigateByImgClick: true,

              tPrev: 'Previous (Left arrow key)', // title for left button
  tNext: 'Next (Right arrow key)', // title for right button
  tCounter: '<span class="mfp-counter">%curr% of %total%</span>' 
            
  }, 
       image: {  verticalFit: false ,
       cursor: 'mfp-zoom-out-cur',},
      
       zoom: {enabled: true,   duration: 500 ,easing: 'ease-in-out' }


 }); 




 $('#open-popup07').magnificPopup({
    items: [
      {
        src: '/assets/images/siteImade/07/07_01.png',
        title: '영광손해사정',
      },     
      {
        src: '/assets/images/siteImade/07/07_02.png',
        title: '영광손해사정',
      },     
      {
        src: '/assets/images/siteImade/07/07_03.png',
        title: '영광손해사정',
      },     
      {
        src: '/assets/images/siteImade/07/07_04.png',
        title: '영광손해사정',
      }     
          
    
    ],    
  type: 'image',
       closeOnContentClick: true,
       closeBtnInside: true,
       fixedContentPos: true,
    gallery: { 
            enabled: true,
            preload: [0,2],
            navigateByImgClick: true,

              tPrev: 'Previous (Left arrow key)', // title for left button
  tNext: 'Next (Right arrow key)', // title for right button
  tCounter: '<span class="mfp-counter">%curr% of %total%</span>' 
            
  }, 
       image: {  verticalFit: false ,
       cursor: 'mfp-zoom-out-cur',},
      
       zoom: {enabled: true,   duration: 500 ,easing: 'ease-in-out' }


 }); 


 $('#open-popup08').magnificPopup({
    items: [
      {
        src: '/assets/images/siteImade/08/08_01.png',
        title: '토탈지게차서비스',
      },     
      {
        src: '/assets/images/siteImade/08/08_02.png',
        title: '토탈지게차서비스',
      },     
      {
        src: '/assets/images/siteImade/08/08_03.png',
        title: '토탈지게차서비스',
      }   
          
    
    ],    
  type: 'image',
       closeOnContentClick: true,
       closeBtnInside: true,
       fixedContentPos: true,
    gallery: { 
            enabled: true,
            preload: [0,2],
            navigateByImgClick: true,

              tPrev: 'Previous (Left arrow key)', // title for left button
  tNext: 'Next (Right arrow key)', // title for right button
  tCounter: '<span class="mfp-counter">%curr% of %total%</span>' 
            
  }, 
       image: {  verticalFit: false ,
       cursor: 'mfp-zoom-out-cur',},
      
       zoom: {enabled: true,   duration: 500 ,easing: 'ease-in-out' }


 }); 


 $('#open-popup09').magnificPopup({
    items: [
      {
        src: '/assets/images/siteImade/09/09_01.png',
        title: '학원시안',
      },     
      {
        src: '/assets/images/siteImade/09/09_02.png',
        title: '학원시안',
      }
          
    
    ],    
  type: 'image',
       closeOnContentClick: true,
       closeBtnInside: true,
       fixedContentPos: true,
    gallery: { 
            enabled: true,
            preload: [0,2],
            navigateByImgClick: true,

              tPrev: 'Previous (Left arrow key)', // title for left button
  tNext: 'Next (Right arrow key)', // title for right button
  tCounter: '<span class="mfp-counter">%curr% of %total%</span>' 
            
  }, 
       image: {  verticalFit: false ,
       cursor: 'mfp-zoom-out-cur',},
      
       zoom: {enabled: true,   duration: 500 ,easing: 'ease-in-out' }


 }); 


 $('#open-popup10').magnificPopup({
    items: [
      {
        src: '/assets/images/siteImade/10/10_01.png',
        title: '(주) 회산',
      },     
      {
        src: '/assets/images/siteImade/10/10_02.png',
        title: '(주) 회산',
      },     
      {
        src: '/assets/images/siteImade/10/10_03.png',
        title: '(주) 회산',
      },     
      {
        src: '/assets/images/siteImade/10/10_04.png',
        title: '(주) 회산',
      }     
          
    
    ],    
  type: 'image',
       closeOnContentClick: true,
       closeBtnInside: true,
       fixedContentPos: true,
    gallery: { 
            enabled: true,
            preload: [0,2],
            navigateByImgClick: true,

              tPrev: 'Previous (Left arrow key)', // title for left button
  tNext: 'Next (Right arrow key)', // title for right button
  tCounter: '<span class="mfp-counter">%curr% of %total%</span>' 
            
  }, 
       image: {  verticalFit: false ,
       cursor: 'mfp-zoom-out-cur',},
      
       zoom: {enabled: true,   duration: 500 ,easing: 'ease-in-out' }


 }); 






});

</script>