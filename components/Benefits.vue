<template>
    <div class="BG bg-[#B3C890] w-full">
        <div class="bg-[#BAE9C7] ml-10 rounded-l-3xl p-5 dropshadow1">
            <h1 class="text-5xl text-center text-green-800 py-4 uppercase font-black">like what you see?</h1>
            <div class="flex px-5 pb-10">
                <div class="w-1/3 text-xl p-5 text-right text-[#076269]">
                    <p>Lorem ipsum dolor sit amet. Id consequuntur adipisci et voluptatem quia aut unde voluptas. Qui
                        tempora
                        enim ex dolor animi ab deleniti laudantium.</p>
                    <p>Lorem ipsum dolor sit amet. Id consequuntur adipisci et voluptatem quia aut unde voluptas.</p>
                    <span>
                        <p class="text-2xl font-bold mt-20">See more ></p>
                    </span>
                </div>
                <div
                    class="text-xl w-2/3 px-10 py-4 bg-[#EAEDC4] rounded-l-lg text-[#076269] font-semibold dropshadow animate-zoom animate-float">
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
        transform: translateY(0);
    }

    50% {
        transform: translateY(-10px);
    }

    100% {
        transform: translateY(0);
    }
}

.animate-zoom {
    animation: zoom-in 2s forwards;
}

.animate-float {
    animation: float 2s infinite;
}
</style>