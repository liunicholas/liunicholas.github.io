---
layout: post
title:  "Second Season: Relic Recovery 2017-2018"
date:   2021-04-24
category: Robotics
---
<img src="/categories/robotics/assets/postImages/RelicRecovery.png" style="width:50%" class="center">

#### &nbsp;&nbsp;&nbsp;&nbsp; In our second season of FTC, we wanted to build with more robust techniques, so we started learning 3D design with CAD and 3D printing. Additionally, we tried fabricating all of the parts ourselves using only metal bars, L beams, and C channels. Of course, we overestimated our measuring and cutting accuracy which resulted in many mechanical issues throughout the season. This was also the first year we used mecanum wheels. We made the mistake of choosing VEX mecanums which broke the night before the San Diego Regionals. Luckily, we emailed Mr. Pruitt, our science teacher from The Bishop's School, and he loaned us a set. Overall, this season was one of much tehnical and team learning.

<img src="/categories/robotics/assets/postImages/relicrecoveryMe.jpeg" style="width:100%" class="center">

<style>
/* Slideshow container */
.slideshow-container {
  <!-- max-width: 100%;
  position: relative;
  margin: auto; -->
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}
</style>

<body>

<div class="slideshow-container">

<div class="mySlides">
  <!-- <div class="numbertext">1 / 4</div> -->
  <img src="/categories/robotics/assets/postImages/rrFront.jpg" style="width:100%">
  <h3 class="text">Front</h3>
</div>

<div class="mySlides">
  <!-- <div class="numbertext">2 / 4</div> -->
  <img src="/categories/robotics/assets/postImages/rrRight.jpg" style="width:100%">
  <h3 class="text">Right</h3>
</div>

<div class="mySlides">
  <!-- <div class="numbertext">3 / 4</div> -->
  <img src="/categories/robotics/assets/postImages/rrBack.jpg" style="width:100%">
  <h3 class="text">Rear</h3>
</div>

<div class="mySlides">
  <!-- <div class="numbertext">4 / 4</div> -->
  <img src="/categories/robotics/assets/postImages/rrLeft.jpg" style="width:100%">
  <h3 class="text">Left</h3>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>
</body>
