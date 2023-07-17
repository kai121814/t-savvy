<template>
  <div class="navbar fixed top-0 left-0 w-full bg-gradient-to-b from-[#9FBE6C] to-[#DBDFAA] shadow-lg">
    <a class="navbar-link" href="#home">Home</a>
    <a class="navbar-link" href="#lessons">Lessons</a>
    <a class="navbar-link" href="#benefits">Benefits</a>
    <a class="navbar-link" href="#packages">Packages</a>
    <a class="navbar-link" href="#testimonies">Testimonies</a>
    <a class="navbar-link" href="#contacts">Contacts</a>
  </div>
</template>

<style scoped>
.navbar-link {
  @apply inline-block px-4 py-3 text-black uppercase font-bold;
  @apply hover:text-white;
}

.navbar-link:hover {
  @apply bg-teal-700;
}
</style>