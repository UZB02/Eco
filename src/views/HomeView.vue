<template>
  <section class="page1 w-full bg-slate-400" style="height:90vh;">
    <div class="container m-0 m-auto flex gap-4 items-center justify-center flex-col top-36 absolute">
      <SVGS />
      <div class="info flex flex-col items-center gap-8 justify-center" style="height: 75vh;">
        <h1 class="text-6xl font-bold text-yellow-200 " style="text-shadow: 0 0 5px #aaa;">YAGONA TOZOLOV XIZMATI</h1>
        <p class="w-1/2 text-xl p-3 rounded-xl shadow text-yellow-50"
          style="text-shadow: 0 0 5px #000; background: rgba(192, 192, 192, 0.285);">Lorem ipsum dolor sit amet
          consectetur adipisicing elit. Vitae optio facilis fugiat illo aliquam sunt aliquid dolores! Maiores, quo
          doloremque deserunt excepturi ullam consectetur unde nihil.</p>
      </div>
    </div>
  </section>
</template>

<script>
import SVGS from "../components/svgss/Main.vue"
export default {
  components: {
    SVGS
  }
}
</script>
<style scoped>
.page1 {
  background: url("../components/img/photo_2023-12-12_10-47-31.jpg");
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
}

@media screen and (max-width: 600px) {
  .page1 {
    background-position: center;
  }

  h1 {
    text-align: center;
    font-size: 3em;
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

@media screen and (max-width: 350px) {
  .page1 {
    background-position: center;
  }

  h1 {
    text-align: center;
    font-size: 2em;
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

@media screen and (max-width: 450px) {
  .page1 {
    background-position: center;
  }

  h1 {
    text-align: center;
    font-size: 2em;
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
}</style>