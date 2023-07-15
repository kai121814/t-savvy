<template>
  <div class="flex bg-gradient-to-b from-[#9FBE6C] to-[#DBDFAA] custom-shadow px-10">
    <a class="block px-10 py-3 text-black uppercase font-bold" href="#home">Home</a>
    <a class="block px-10 py-3 text-black uppercase font-bold" href="#news">News</a>
    <a class="block px-10 py-3 text-black uppercase font-bold" href="#contact">Contact</a>
    <a class="block px-10 py-3 text-black uppercase font-bold" href="#about">About</a>
  </div>
</template>

<style scoped>
.custom-shadow {
  --shadow-opacity: 0.35;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, var(--shadow-opacity));
}
</style>