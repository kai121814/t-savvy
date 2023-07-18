<template>
    <div class="BG bg-[#B3C890] w-full cursor-default pt-20" id="benefits">
        <div class="bg-[#BAE9C7] lg:ml-10 sm:ml-5 lg:rounded-l-3xl sm:place-content-center lg:p-5 dropshadow1">
            <h1 class="text-5xl text-center text-green-800 py-4 uppercase font-black">like what you see?</h1>
            <div class="lg:flex sm:grid lg:px-5 sm:mx-2 pb-10">
                <div class="lg:w-1/3 sm:w-full text-xl p-5 lg:text-right text-[#076269]">
                    <p>
                        Lorem ipsum dolor sit amet. Id consequuntur adipisci et voluptatem quia aut unde voluptas. Qui
                        tempora
                        enim ex dolor animi ab deleniti laudantium.
                    </p>
                    <p>Lorem ipsum dolor sit amet. Id consequuntur adipisci et voluptatem quia aut unde voluptas.</p>
                </div>
                <div class="flex justify-center w-full px-5">
                    <div class="text-xl w-full mx-auto px-5 py-4 bg-[#EAEDC4] 
                    rounded-l-lg text-[#076269] font-semibold dropshadow animate-zoom animate-float">
                        <h2 class="text-center text-3xl font-bold">Benefits</h2>
                        <ul>
                            <li>Item 1</li>
                            <li>Item 2</li>
                            <li>Item 3</li>
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
  