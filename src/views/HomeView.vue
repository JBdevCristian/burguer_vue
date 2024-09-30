<template>
  <Banner />
  <div class="main-container">
    <h1>Monte o seu burguer: </h1>
    <FormBurguer />
  </div>
</template>

<script>
import Banner from '../components/Banner.vue'
import FormBurguer from '../components/BurguerForm.vue'

export default {
  name: 'Home',
  components: {
    Banner,
    FormBurguer
  }
}
</script>

<style escoped>
  body {
    max-height: 100vh;
    height: auto;
  }
</style>
