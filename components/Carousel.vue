<template>
  <div class="slideshow-container w-full mx-auto h-auto fade" id="home">
    <div class="Containers">
      <div class="image-container">
        <div class="overlay"></div>
        <div class="flex w-full bg-[#B2CB88] ">
          <img src="~/assets/img/vision.png " class="carousel-image bg-[#B2CB88] ">
          <div class="bg-[#B2CB88] w-1/3"></div>
        </div>

        <div class="caption">
          <h1 class="caption-header">Vision</h1>
          <p class="caption-text">To empower and support developers in their career growth, foster a vibrant and
            collaborative community, and connect talented individuals with rewarding opportunities in the IT industry.</p>
        </div>
      </div>
    </div>

    <div class="Containers">
      <div class="image-container">
        <div class="flex flex-wrap w-full bg-[#B2CB88] ">
          <div class="w-1/3 bg-black left-0 h-full"></div>
          <div class="overlay2"></div>
        </div>
        
        <div class="flex w-full bg-[#B2CB88] ">
          <div class="bg-[#B2CB88] w-1/3"></div>
          <img src="~/assets/img/mission.png" class="carousel-image bg-[#B2CB88] ">
        </div>
        <div class="caption">
          <h1 class="caption-header">Mission</h1>
          <p class="caption-text">To enhance the skills and knowledge of developers, facilitate networking and
            knowledge-sharing among community members, and assist job seekers in finding fulfilling roles in the IT
            Industry.</p>
        </div>
      </div>
    </div>

    <a class="Back text-6xl" @click="plusSlides(-1)">&#10094;</a>
    <a class="forward text-6xl" @click="plusSlides(1)">&#10095;</a>
  </div>

  <br>

  <div style="text-align:center">
    <span class="dots" @click="currentSlide(1)"></span>
    <span class="dots" @click="currentSlide(2)"></span>
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
  @apply w-2/3 h-screen object-cover;
}

.image-container {
  @apply relative;
}

.overlay {
  @apply absolute top-0 left-0 h-full w-2/3 bg-gradient-to-l from-[#B2CB88] to-transparent;
}
.overlay2 {
  @apply absolute top-0 left-0 h-full w-full bg-gradient-to-r from-[#B2CB88] to-transparent;
}
.caption {
  @apply absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 text-white text-center;
}

.caption-header {
  @apply text-[#4AA3AA] text-outline text-6xl font-bold mb-16;
}

.text-outline {
  text-shadow: 0 0 5px white, 0 0 4px white, 0 0 4px white, 0 0 2px white;
}

.caption-text {
  @apply text-white text-3xl;
}

.Containers {
  @apply hidden bg-no-repeat bg-contain;
}

.Back,
.forward {
  @apply cursor-pointer absolute top-1/2 text-teal-500 font-bold rounded-full select-none;
  @apply py-2 px-10;
  @apply -mt-12;
}

.forward {
  @apply right-0 rounded-full;
}

.Back:hover,
.forward:hover {
  @apply bg-teal-800 bg-opacity-50;
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

.enable,
.dots:hover {
  @apply bg-gray-700;
}

/* .fade {
  @apply animation-fade;
} */

@keyframes fade {
  from {
    opacity: .5
  }

  to {
    opacity: 2
  }
}
</style>
