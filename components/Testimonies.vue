<template>
  <div class="BG flex flex-col items-center mx-auto cursor-default" id="testimonies">
    <h1 class="text-4xl md:text-6xl font-bold text-[#4AA3AA] py-6">
      <span class="text-outline"></span>
      <span class="text-[#F5F0BB] px-3 bg-gradient-to-r to-[#9FBE6C] from-[#4AA3AA]">Testimonies</span>
    </h1>
    <div class="border align-end relative custom-border">
      <div class="circle"></div>
      <p class="testimonial-text text-sm md:text-3xl md:pl-1 pl-16">This Code Camp has helped me get the job of my dreams.</p>
    </div>
    <div class="border align-left relative custom-border">
      <div class="circle2"></div>
      <p class="testimonial-text md:pr-1 pr-16">This Code Camp has helped me get the job of my dreams.</p>
    </div>
    <div class="border align-end relative custom-border">
      <div class="circle"></div>
      <p class="testimonial-text text-sm md:text-3xl md:pl-1 pl-16">This Code Camp has helped me get the job of my dreams.</p>
    </div>
  </div>
</template>

<style>
.circle {
  @apply w-24 h-24 md:w-52 md:h-52 rounded-full bg-[#B3C890] -ml-4 absolute top-1/2 left-0 transform -translate-y-1/2;
}

.circle2 {
  @apply w-24 h-24 md:w-52 md:h-52 rounded-full bg-[#B3C890] -mr-4 absolute top-1/2 right-0 transform -translate-y-1/2;
}

.custom-border {
  @apply border border-4 border-[#B3C890] bg-[#DBDFAA] py-4 md:py-12 px-3 md:px-5 rounded-md relative mb-4 md:mb-8 w-11/12 font-sans text-sm md:text-3xl;
  border-radius: 40px;
}

.align-end {
  @apply text-right;
}

.align-left {
  @apply text-left;
}

.testimonial-text {
  @apply mt-2 md:mt-4;
}

.title {
  @apply uppercase text-teal-500 outline-white outline-2 text-5xl font-bold;
}

.BG {
  @apply py-5;
}
</style>
