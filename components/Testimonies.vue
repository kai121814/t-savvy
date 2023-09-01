<template>
  <div class="lg:pt-2 pt-16" id="testimonies"></div>
  <div class="BG flex flex-col items-center mx-auto cursor-default mb-10">
    <h1 class="text-4xl md:text-6xl font-bold text-[#4AA3AA] lg:py-16 py-4">
      <span class="text-outline"></span>
      <span class="text-[#F5F0BB] px-3 text-outline">Testimonies</span>
    </h1>
    <div class="border align-end relative custom-border my-5">
      <div class="circle border-spacing-2 border-8 border-white bg-cover bg-center"
        style="background-image: url('/assets/img/carl.jpg')"></div>
      <div class="w-5/6 ml-auto mr-5">
        <p class="testimonial-text text-sm md:text-2xl md:pl-1 pl-20">The program hasn't even ended, but I've already
          learned a lot and had a fantastic experience at Tech Savvy Code Camp. This coding camp has helped me develop the
          skills needed in web development.</p>
      </div>
    </div>

    <div class="border align-left relative custom-border my-5">
      <div class="circle2 border-spacing-2 border-8 border-white bg-cover bg-center"
        style="background-image: url('/assets/img/pearl.jpg')"></div>
        <div class="ml-5 w-5/6">
          <p class="testimonial-text text-sm md:text-2xl md:pr-1 pr-16">I joined Tech Savvy in mid-August, 
        and what truly impressed me about Tech Savvy is the strong sense of community 
        they nurture. Through hands-on teaching, interactive discussions, and fostering 
        a supportive network of like-minded learners. Aside from that, having knowledgeable 
        instructors and seniors who are not only experts in their field but also deeply 
        enthusiastic and passionate about teaching, enhancing the overall learning experience.</p>
        </div>
      
    </div>
    <div class="border align-end relative custom-border my-5">
      <div class="circle border-spacing-2 border-8 border-white bg-cover bg-center"
        style="background-image: url('/assets/img/kai.jpg')"></div>
      <div class="w-5/6 ml-auto mr-5">
        <p class="testimonial-text text-sm md:text-2xl md:pl-1 pl-16">
          Tech Savvy is a blessing to me. I was looking for a bootcamp 
          in Misamis Occidental to enhance my skills in programming 
          and web development, and I found this one in the heart of 
          Ozamiz City. It has helped me develop my coding skills and 
          has been a great support system for me as a computer science 
          student. It is more than just a bootcamp; it is a family.</p>
      </div>

    </div>
  </div>
</template>

<style>
.text-outline {
  text-shadow: 5px 5px 0 black, 5px 5px 0 black, 5px 5px 0 black, 5px 5px 0 black;
}

.circle {
  @apply w-24 h-24 md:w-52 md:h-52 rounded-full lg:-ml-10 ml-2 absolute top-1/2 left-0 transform -translate-y-1/2;
}

.circle2 {
  @apply w-24 h-24 md:w-52 md:h-52 rounded-full bg-[#f7f7f7] lg:-mr-4 mr-2 absolute top-1/2 right-0 transform -translate-y-1/2;
}

.custom-border {
  @apply border-4 border-white bg-transparent py-2 md:py-12 px-3 md:px-5 rounded-md relative mb-4 md:mb-8 w-11/12 font-sans text-sm md:text-3xl;
  border-radius: 40px;
}

.align-end {
  @apply text-right;
}

.align-left {
  @apply text-left;
}

.testimonial-text {
  @apply mt-2 text-white;
}

.title {
  @apply uppercase text-teal-500 outline-white outline-2 text-5xl font-bold;
}

.BG {
  @apply py-5;
}
</style>
