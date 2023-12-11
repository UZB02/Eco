<template>
    <section class="page1 w-full bg-slate-400" style="height:90vh;">
        <div class="container m-0 m-auto flex gap-4 items-center justify-center flex-col top-36 absolute">
            <!-- <div class="image w-full flex items-center justify-end">
        <img src="../components/img/icon.jpg"
          class="rounded-full w-2/12">
        </div> -->
            <div class="info flex flex-col items-center gap-8 justify-center" style="height: 75vh;">
                <h1 class="text-6xl font-bold text-yellow-200" style="text-shadow: 0 0 5px #aaa;">ECO CLEAN</h1>
                <p class="w-1/2 text-xl p-3 rounded-xl shadow text-yellow-50"
                    style="text-shadow: 0 0 5px #000; background: rgba(192, 192, 192, 0.285);">Lorem ipsum dolor sit amet
                    consectetur adipisicing elit. Vitae optio facilis fugiat illo aliquam sunt aliquid dolores! Maiores, quo
                    doloremque deserunt excepturi ullam consectetur unde nihil.</p>
            </div>
        </div>
    </section>
</template>

<script setup></script>
<style scoped>
.page1 {
    background: url("https://dta0yqvfnusiq.cloudfront.net/envirocleanusa/2019/04/dreamstime-xxl-103309954-5cae5f610cf77.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    /* background-position: center; */
}

@media screen and (max-width: 600px) {
    .page1{
        background-position: center;
    }
    img {
        width: 50%;
    }

    .info {
        width-space: nowrap;
        overflow: hidden;
        text-overflow: ellipsis;
    }

    .info p {
        text-align: center;
        font-size: 1em;
        width: 100%;
    }
}
</style>