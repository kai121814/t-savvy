<template>
  <div class="slideshow-container w-full mx-auto h-3/6 fade"  id="home">
    <div class="Containers">
      <div class="MessageInfo">1 / 3</div>
      <img src="~/assets/img/vision.png" class="carousel-image">
      <div class="Info">First caption</div>
    </div>

    <div class="Containers">
      <div class="MessageInfo">2 / 3</div>
      <img src="~/assets/img/vision.png" class="carousel-image">
      <div class="Info">Second Caption</div>
    </div>

    <div class="Containers">
      <div class="MessageInfo">3 / 3</div>
      <img src="~/assets/img/vision.png" class="carousel-image">
      <div class="Info">Third Caption</div>
    </div>

    <a class="Back" @click="plusSlides(-1)">&#10094;</a>
    <a class="forward" @click="plusSlides(1)">&#10095;</a>
  </div>

  <br>

  <div style="text-align:center">
    <span class="dots" @click="currentSlide(1)"></span>
    <span class="dots" @click="currentSlide(2)"></span>
    <span class="dots" @click="currentSlide(3)"></span>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue';

const slidePosition = ref(1);

onMounted(() => {
  slideShow();
});

function plusSlides(n) {
  slideShow(slidePosition.value += n);
}

function currentSlide(n) {
  slideShow(slidePosition.value = n);
}

function slideShow(n) {
  const slides = document.getElementsByClassName("Containers");
  const circles = document.getElementsByClassName("dots");
  if (n > slides.length) slidePosition.value = 1;
  if (n < 1) slidePosition.value = slides.length;
  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (let i = 0; i < circles.length; i++) {
    circles[i].className = circles[i].className.replace(" enable", "");
  }
  slides[slidePosition.value - 1].style.display = "block";
  circles[slidePosition.value - 1].className += " enable";
}
</script>

<style scoped>
/* Tailwind CSS classes */

/* Slideshow container */
.slideshow-container {
  @apply mx-auto relative;
}

/* Image styling */
.carousel-image {
  @apply w-full object-cover;
}

.Containers {
  @apply hidden bg-no-repeat bg-contain;
}

.Back, .forward {
  @apply cursor-pointer absolute top-1/2 text-neutral-500 font-bold text-xl rounded-full select-none;
  @apply py-2 px-4;
  @apply -mt-12;
}

.forward {
  @apply right-0 rounded-l-none;
}

.Back:hover, .forward:hover {
  @apply bg-black bg-opacity-80;
}

.Info {
  @apply text-white text-base absolute bottom-4 w-full text-center;
  @apply py-2 px-4;
  @apply bg-black bg-opacity-50;
  
}

.MessageInfo {
  @apply text-white text-sm absolute top-0;
  @apply py-2 px-4;
}

.dots {
  @apply cursor-pointer inline-block h-4 w-4 mx-1 bg-gray-300 rounded-full;
}

.enable, .dots:hover {
  @apply bg-gray-700;
}

/* .fade {
  @apply animation-fade;
} */

@keyframes fade {
  from {opacity: .5}
  to {opacity: 2}
}
</style>