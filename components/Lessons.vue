<template>
  <div class="w-full bg-[url('../assets/bg/BG.png')] bg-no-repeat bg-cover">
    <div class="container flex items-center mx-auto w-full">
      <h1 class="my-10 text-6xl font-bold text-[#4AA3AA] "><span class="text-outline">WHAT WE </span><span
          class="text-[#F5F0BB] px-3 bg-gradient-to-r to-[#9FBE6C] from-[#4AA3AA]">TEACH</span></h1>
      <div class="flex w-full">
        <div class="bg-[#DBDFAA] w-1/5 h-80 m-3 p-5 flex text-center justify-center blue-shadow">
          <p class="text-[#076269] font-bold text-2xl">FIGMA</p>
        </div>
        <div class="bg-[#DBDFAA] w-1/5 h-80 m-3 p-5 flex text-center justify-center blue-shadow">
          <p class="text-[#076269] font-bold text-2xl">HTML | CSS | JAVASCRIPT</p>
        </div>
        <div class="bg-[#DBDFAA] w-1/5 h-80 m-3 p-5 flex text-center justify-center blue-shadow">
          <p class="text-[#076269] font-bold text-2xl">NUXT.JS | TAILWINDCSS | TYPESCRIPT</p>
        </div>
        <div class="bg-[#DBDFAA] w-1/5 h-80 m-3 p-5 flex text-center justify-center blue-shadow">
          <p class="text-[#076269] font-bold text-2xl">PYTHON</p>
        </div>
        <div class="bg-[#DBDFAA] w-1/5 h-80 m-3 p-5 flex text-center justify-center blue-shadow">
          <p class="text-[#076269] font-bold text-2xl">DJANGO</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.text-outline {
  text-shadow: 0 0 5px white, 0 0 4px white, 0 0 4px white, 0 0 2px white;
}
.blue-shadow {
  box-shadow: 7px 7px 2px 0 rgba(100, 180, 186, 0.5);
}
</style>