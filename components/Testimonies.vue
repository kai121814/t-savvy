<template>
  <div class="BG flex flex-col items-center mx-auto">
    <h1 class=" text-6xl font-bold text-[#4AA3AA] "><span class="text-outline"></span><span
          class="text-[#F5F0BB] px-3 bg-gradient-to-r to-[#9FBE6C] from-[#4AA3AA]">Testimonies</span></h1>
    <div class="border align-end relative custom-border">
      <div class="w-52 h-52 rounded-full bg-[#B3C890] -ml-8 absolute top-1/2 left-0 transform -translate-y-1/2"></div>
      This Code Camp has helped me get the job of my dreams.
    </div>
    <div class="border align-left relative custom-border">
      <div class="circle2"></div>
      This Code Camp has helped me get the job of my dreams.
    </div>
    <div class="border align-end relative custom-border">
      <div class="w-52 h-52 rounded-full bg-[#B3C890] -ml-8 absolute top-1/2 left-0 transform -translate-y-1/2 "></div>
      This Code Camp has helped me get the job of my dreams.
    </div>
  </div>
</template>

<style>

.circle {
  @apply w-52 h-52 rounded-full bg-[#B3C890] -ml-8 absolute top-1/2 left-0 transform -translate-y-1/2 ;
}

.circle2 {
  @apply w-52 h-52 rounded-full bg-[#B3C890] -mr-8 absolute top-1/2 right-0 transform -translate-y-1/2;
}

.custom-border {
  @apply border border-4  border-[#B3C890] bg-[#DBDFAA] py-12 px-5 rounded-md relative mb-8 w-11/12 font-sans my-10 text-3xl;
  border-top-left-radius: 40px;
  border-bottom-left-radius: 40px;
  border-top-right-radius: 40px;
  border-bottom-right-radius: 40px;
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
