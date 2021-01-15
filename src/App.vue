<template>
  <section>
    <home></home>
  </section>
  
</template>

<script>
import home from './components/home.vue'

export default {
  name: 'App',
  components: {
    'home' : home,
  }
}
</script>

<style scoped>

  section {
    overflow-y: hidden;
  }

</style>
