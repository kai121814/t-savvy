<template>
    <div class="container">
        <h1 class="title">like what you see?</h1>
        <div class="flex">
            <div class="box box1">
                <p>Lorem ipsum dolor sit amet. Id consequuntur adipisci et voluptatem quia aut unde voluptas. Qui tempora
                    enim ex dolor animi ab deleniti laudantium.</p>
                    <p>Lorem ipsum dolor sit amet. Id consequuntur adipisci et voluptatem quia aut unde voluptas.</p>
            </div>
            <div class="box box2">
                <h2 style="text-align: center;">Benefits</h2>
                <ul>
                    <li>Item 1</li>
                    <li>Item 2</li>
                    <li>Item 3</li>
                    <!-- Add more list items as needed -->
                </ul>
            </div>
        </div>
    </div>
</template>
  
<style scoped>
.container {
    display: flex;
    justify-content: center;
    background-color: #BAE9C7;
}

.flex {
    display: flex;
    align-items: center;
    margin: auto;
}

.title {
    color: #6E7E52;
}

.box1 {
    width: 50%;
    height: 100%;
}

.box2 {
    width: 50%;
    height: 100%;
    background-color: #EAEDC4;
   border-top-left-radius: 15px;
   border-bottom-left-radius: 15px;
}
</style>