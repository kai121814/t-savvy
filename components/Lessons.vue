<template>
  <div class="BG w-full pt-1 bg-[url('../assets/bg/BG.png')] bg-no-repeat bg-cover cursor-default" id="lessons">
    <div class="flex flex-col items-center mx-auto w-full">
      <h1 class="my-10 text-6xl font-bold text-[#4AA3AA] "><span class="text-outline">WHAT WE </span><span
          class="text-[#F5F0BB] px-3 bg-gradient-to-r to-[#9FBE6C] from-[#4AA3AA] text-animation">
          <span class="text-animation">T</span>
          <span class="text-animation">E</span>
          <span class="text-animation">A</span>
          <span class="text-animation">C</span>
          <span class="text-animation">H</span></span></h1>

      <!-- boxes content -->
      <div class="flex w-full items-stretch">
        <div class="bg-[#DBDFAA] self-center w-1/5 h-72 m-3 p-5 flex text-center justify-center blue-shadow animate-zoom">
          <p class="text-[#076269] font-bold text-2xl">FIGMA</p>
        </div>
        <div class="bg-[#DBDFAA] self-center w-1/5 h-80 m-3 p-5 flex text-center justify-center blue-shadow animate-zoom">
          <p class="text-[#076269] font-bold text-2xl">HTML, CSS JAVASCRIPT</p>
        </div>
        <div class="bg-[#DBDFAA] self-center w-1/5 h-96 m-3 p-5 flex text-center justify-center blue-shadow animate-zoom">
          <p class="text-[#076269] font-bold text-2xl">NUXT.JS TAILWINDCSS TYPESCRIPT</p>
        </div>
        <div class="bg-[#DBDFAA] self-center w-1/5 h-80 m-3 p-5 flex text-center justify-center blue-shadow animate-zoom">
          <p class="text-[#076269] font-bold text-2xl">PYTHON</p>
        </div>
        <div class="bg-[#DBDFAA] self-center w-1/5 h-72 m-3 p-5 flex text-center justify-center blue-shadow animate-zoom">
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

.BG {
  padding-top: 5%;
}

@keyframes zoom-in {
  0% {
    opacity: 0;
    transform: scale(0.2);
  }

  100% {
    opacity: 1;
    transform: scale(1);
  }
}

.animate-zoom {
  animation: zoom-in 1s forwards;
}

@keyframes typing {
  0% {
    opacity: 0;
    transform: translateX(-10px);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.text-animation {
  display: inline-block;
  opacity: 0;
  animation: typing 2s ease-in-out;
  animation-fill-mode: forwards;
}

.text-animation:nth-child(2) {
  animation-delay: 0.2s;
}

.text-animation:nth-child(3) {
  animation-delay: 0.4s;
}

.text-animation:nth-child(4) {
  animation-delay: 0.6s;
}

.text-animation:nth-child(5) {
  animation-delay: 0.8s;
}

.text-animation:nth-child(6) {
  animation-delay: 1s;
}
</style>