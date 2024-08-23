<template>
  <firstcomp text="hello from atom"></firstcomp>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</template>

<script>
import firstcomp from "../components/firstcomp.vue";
import '../assets/main.css'
export default {
  name:'HomeView',
  components: {
    firstcomp
  }
}
</script>
