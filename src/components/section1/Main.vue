<template>
    <section class="page1 w-full bg-slate-400" style="height:90vh;">
        <div class="container m-0 m-auto flex gap-4 items-center justify-center flex-col top-36 absolute">
           <div class="image w-full flex items-center justify-center"><img src="./icon.jpg" class="rounded-full w-2/12"></div>
           <div class="info flex flex-col items-center justify-center">
            <h1 class="text-6xl font-bold text-yellow-200" style="text-shadow: 0 0 5px #aaa;">ECO CLEAN</h1>
             <p class="w-1/2 text-xl p-3 rounded-xl shadow text-yellow-50" style="text-shadow: 0 0 5px #000; background: rgba(192, 192, 192, 0.285);">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae optio facilis fugiat illo aliquam sunt aliquid dolores! Maiores, quo doloremque deserunt excepturi ullam consectetur unde nihil.</p>
             
           </div>
        </div>
    </section>
    </template>

<script setup></script>
<style scoped>
.page1{
    background: url("https://wecleananyhome.com/wp-content/uploads/slide1-1532x766.jpg");
}
@media screen and (max-width: 600px) {
    img{
        width:50%;
    }
    .info{
width-space: nowrap;
        overflow:hidden;
        text-overflow: ellipsis;
    }
    .info p{
        text-align: center;
        font-size: 1em;
        width:100%;
    }
}
</style>