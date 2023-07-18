<script setup>
const scrollToSection = (sectionId) => {
  const section = document.getElementById(sectionId);
  if (section) {
    section.scrollIntoView({ behavior: 'smooth' });
  }
};
</script>

<template>
  <div class="navbar fixed top-0 left-0 w-full bg-gradient-to-b from-[#9FBE6C] to-[#DBDFAA] shadow-lg z-50 cursor-pointer">
    <a class="navbar-link" @click="scrollToSection('home')">Home</a>
    <a class="navbar-link" @click="scrollToSection('lessons')">Lessons</a>
    <a class="navbar-link" @click="scrollToSection('benefits')">Benefits</a>
    <a class="navbar-link" @click="scrollToSection('packages')">Packages</a>
    <a class="navbar-link" @click="scrollToSection('testimonies')">Testimonies</a>
    <a class="navbar-link" @click="scrollToSection('contacts')">Contacts</a>
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