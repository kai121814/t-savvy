<template>
  <div>
    <Carousel :autoplay="true" :loop="true" :perPage="1" :navigationEnabled="true">
      <Slide v-for="(item, index) in carouselItems" :key="index">
        <img :src="item.image" alt="Carousel Slide" class="w-full">
      </Slide>
    </Carousel>
  </div>
</template>

<script setup>
import { Carousel, Slide } from 'vue-carousel';

const carouselItems = [
  { image: 'path-to-image1.jpg' },
  { image: 'path-to-image2.jpg' },
  { image: 'path-to-image3.jpg' },
];
</script>

<style>
/* Additional styles specific to the carousel can be added here */
</style>