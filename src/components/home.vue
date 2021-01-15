<template>
  <main>
    <h1><span class="acarn">A</span>NDREW</h1>
    <h1 class="line2"><span class="acarn">CARN</span>AGHAN</h1>
  </main>
</template>

<script>
export default {
  name: 'home',
}
</script>

<style scoped>

  main {
    overflow-y: hidden;
    align-items: center;
  }

  h1 {
    font-family: 'Playfair Display', serif;
    font-size: 1000%;
    overflow-y: hidden;
    margin: 0;
    letter-spacing: 10px;
    }

  .line2 {
    margin: 0 0 0 10%;
  }

  .acarn {
    text-decoration: underline;  
  }

</style>