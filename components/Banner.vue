<template>
  <div class="slideshow-container w-full mx-auto h-auto fade mb-24" id="home">
  
    <div class="Containers">
      <div class="image-container">
        <div class="absolute top-0 right-0 h-full w-2/3 bg-gradient-to-r from-[#03372A] to-transparent"></div>

        <div class="flex w-full bg-[#03372A] ">
          <div class="bg-[#03372A] w-1/3"></div>
          <img src="~/assets/img/mission.png" class="carousel-image bg-[#03372A] ">
        </div>
        <div class="absolute top-1/2 lg:left-1/4 transform lg:-translate-x-1/2 md:mx-20 mx-10 -translate-y-1/2 text-white text-center lg:w-1/3 w-1/2">
          <h1 class="caption-header">TECHSAVVY CODECAMP</h1>
          <p class="caption-text">Enhancing your skills and knowledge in development, facilitating networking and
            knowledge-sharing among community members. Assisting job seekers in finding fulfilling roles in the IT
            Industry.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>

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

.caption-header {
  @apply text-white font-black text-left lg:text-7xl text-3xl lg:mb-14 mb-5 lg:mt-12;
}

.caption-text {
  @apply text-white font-semibold text-xl lg:text-3xl text-left;
}

.Containers {
  @apply bg-no-repeat bg-contain;
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
