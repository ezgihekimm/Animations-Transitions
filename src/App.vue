<template>
  <div>

    <menu1 />
    <introduction />
    <technicial />
    <Scroll />
    <usage />
    <resim/>
  

    <balon />
  </div>

</template>

<script>
  import 'animate.css'
  import menu1 from './components/menu1.vue'
  import introduction from './components/introduction.vue'
  import technicial from './components/technicial.vue'
  import balon from './components/balon.vue'
  import usage from './components/usage.vue'
  import resim from './components/resim.vue'
  import Scroll from './components/Scroll.vue'
  export default {
    name: 'App',
    components: {
      menu1,
      introduction,
      technicial,
      balon,
      usage,
      resim,
      Scroll

    }

  }
</script>

<style>

</style>