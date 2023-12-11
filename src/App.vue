<script>
import { RouterLink, RouterView } from 'vue-router'
import Nav from "./components/nav_bar/Main.vue"
import Section1 from "./components/section1/Main.vue"
// import Forms from "./components/forms/Main.vue"
export default {
  components: {
    Section1,
    // Forms,
    Nav
  }
}
</script>

<template>
  <section class="w-full">
    <div class="container m-0 m-auto w-full">
      <div class="nav_bar sticky top-0 z-50 w-full">
        <Nav/>
      </div>
      <section class="page1">
        <Section1/>
      </section>
      <!-- <section class="forms">
        <Forms/>
      </section> -->
      <!-- <RouterView /> -->
    </div>
  </section>
</template>

<style scoped></style>
