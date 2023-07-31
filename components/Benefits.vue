<template>
    <div class="BG bg-[#B3C890] w-full cursor-default pt-20" id="benefits">
        <div class="bg-[#BAE9C7] lg:ml-10 sm:ml-5 lg:rounded-l-3xl sm:place-content-center lg:p-5 dropshadow1">
            <h1 class="text-5xl text-center text-green-800 py-4 uppercase font-black">like what you see?</h1>
            <div class="lg:flex sm:grid lg:px-5 sm:mx-2 pb-10">
                <div class="lg:w-1/3 sm:w-full text-xl p-5 lg:text-right text-[#076269]">
                    <p>
                       These are the benefits of choosing to partake in the Tech Savvy Code Camp, a certificate of completion will be given upon creating a functioning e-Resume that clients' will be able to use in applying for an IT job. Being knowledgeable in full stack web development gives you an edge in the industry as you are well-rounded in the areas of web-development. Exclusive merch is available per season and will be different each year. Lastly, being able to attend IT conventions and experience the world of being an IT practitioner and learn from the best in the industry.
                    </p>
                </div>
                <div class="flex justify-center w-full px-5">
                    <div class="text-xl w-full mx-auto px-5 py-4 bg-[#EAEDC4] 
                    rounded-l-lg text-[#076269] font-semibold dropshadow animate-zoom animate-float">
                        <h2 class="text-center text-6xl font-bold mb-12">Benefits</h2>
                        <ul>
                            <li class="text-4xl">Certificate of Completion</li>
                            <hr class="border-solid border-2 rounded mb-5 border-green-300 w-3/6">
                            <li class="text-4xl">e-Resume</li>
                            <hr class="border-solid border-2 rounded mb-5 border-green-300 w-3/6">
                            <li class="text-4xl">Full Stack Web Development</li>
                            <hr class="border-solid border-2 rounded mb-5 border-green-300 w-3/6">
                            <li class="text-4xl">Exclusive Tech Savvy Merch</li>
                            <hr class="border-solid border-2 rounded mb-5 border-green-300 w-3/6">
                            <li class="text-4xl">Attend IT Conventions</li>
                            <hr class="border-solid border-2 rounded mb-5 border-green-300 w-3/6">
                            <li class="text-4xl">Learn from a Software Engineer with a decade long experience in the industry.</li>
                            <hr class="border-solid border-2 rounded mb-5 border-green-300 w-3/6">
                            <!-- Add more list items as needed -->
                        </ul>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>
  
<style scoped>
.dropshadow {
    box-shadow: 7px 7px 2px 0 rgba(0, 0, 0, 0.25);
}

.dropshadow1 {
    box-shadow: 7px 7px 2px 0 rgba(0, 0, 0, 0.25);
}

.BG {
    padding-bottom: 5%;
}

@keyframes zoom-in {
    0% {
        transform: scale(0);
        opacity: 0;
    }

    100% {
        transform: scale(1);
        opacity: 1;
    }
}

@keyframes float {
    0% {
        transform: translateY(5px);
    }

    50% {
        transform: translateY(-20px);
    }

    100% {
        transform: translateY(5px);
    }
}

.animate-zoom {
    animation: zoom-in 2s forwards;
}

.animate-float {
    animation: float 3s infinite;
}
</style>
  