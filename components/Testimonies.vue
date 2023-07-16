<template>
  <div class="BG container mx-auto">
    <h1 class="my-10 text-6xl font-bold text-[#4AA3AA] "><span class="text-outline"></span><span
          class="text-[#F5F0BB] px-3 bg-gradient-to-r to-[#9FBE6C] from-[#4AA3AA]">Testimonies</span></h1>
    <div class="border align-end relative custom-border">
      <div class="circle"></div>
      This Code Camp has helped me get the job of my dreams.
    </div>
    <div class="border align-left relative custom-border">
      <div class="circle2"></div>
      This Code Camp has helped me get the job of my dreams.
    </div>
    <div class="border align-end relative custom-border">
      <div class="circle"></div>
      This Code Camp has helped me get the job of my dreams.
    </div>
  </div>
</template>

<style>
.container {
  @apply flex flex-col items-center mt-36;
}

.circle {
  @apply w-52 h-52 rounded-full bg-green-300 -ml-8 absolute top-1/2 left-0 transform -translate-y-1/2;
}

.circle2 {
  @apply w-52 h-52 rounded-full bg-green-300 -mr-8 absolute top-1/2 right-0 transform -translate-y-1/2;
}

.custom-border {
  @apply border border-green-300 bg-yellow-300 py-12 px-5 rounded-md relative mb-8 w-11/12 font-sans my-10 text-3xl;
}

.align-end {
  @apply text-right;
}

.align-left {
  @apply text-left;
}

.title {
  @apply uppercase text-teal-500 outline-white outline-2 text-5xl font-bold;
}
.BG{
  padding-bottom: 10%;
}
</style>
