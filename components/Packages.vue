<template>
  <div class="BG w-full bg-[url('../assets/bg/BG2.png')] bg-no-repeat bg-cover cursor-default" id="packages">
    <div class="w-full justify-center">
      <div class="w-full flex mx-auto justify-center">
        <h1 class="my-10 lg:text-7xl text-5xl text-[#4AA3AA] px-3 font-black uppercase text-outline">Packages</h1>
      </div>
      <div class="w-full flex flex-wrap mx-auto justify-center items-stretch">

        <div class="lg:w-1/4 lg:h-80 p-7 bg-[#A7D5D8] m-4 rounded-3xl self-center text-center dropshadow animate-zoom cursor-pointer">
          <p class="text-3xl mb-7 font-bold">Online Sessions</p>
          <p class="text-lg">Lorem ipsum dolor sit amet. Id consequuntur adipisci et voluptatem quia
            aut unde voluptas. Qui tempora enim ex dolor animi ab deleniti laudantium.</p>
        </div>

        <div class="lg:w-1/4 lg:h-96 p-7 bg-[#6DB3B8] m-4 rounded-3xl self-center text-center dropshadow animate-zoom cursor-pointer">
          <p class="text-3xl mb-7 font-bold">On-Site Sessions</p>
          <p class="text-lg">Lorem ipsum dolor sit amet. Id consequuntur adipisci et voluptatem quia 
            aut unde voluptas. Qui tempora enim ex dolor animi ab deleniti laudantium.</p>
        </div>

        <div class="lg:w-1/4 lg:h-80 p-7 bg-[#A7D5D8] m-4 rounded-3xl self-center text-center dropshadow animate-zoom cursor-pointer">
          <p class="text-3xl mb-7 font-bold">Advanced Package</p>
          <p class="text-lg">Lorem ipsum dolor sit amet. Id consequuntur adipisci et voluptatem quia 
            aut unde voluptas. Qui tempora enim ex dolor animi ab deleniti laudantium.</p>
        </div>
        
      </div>
    </div>
  </div>
</template>

<style scoped>
.dropshadow {
  box-shadow: 8px 8px 3px 0 rgba(0, 0, 0, 0.25);
}
.text-outline {
  text-shadow: 0 0 5px white, 0 0 4px white, 0 0 4px white, 0 0 2px white;
}
.BG{
  padding-top: 1%;
  padding-bottom: 5%;
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
  animation: zoom-in 2s forwards;
}
</style>

