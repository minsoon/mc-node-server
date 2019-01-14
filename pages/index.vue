<template>
  <section class="container">
    {{ title }}
  </section>
</template>

<script>
  import axios from 'axios'
  export default {
    data () {
      return {
        title: 'mc-nuxt-server'
      }
    }
  }
</script>

<style>
  .container {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    font-family: sans-serif;
  }
  .movie img {
    width: 300px;
    height: 445px;
  }
  .movie h1 {
    margin-top: 5px;
  }
  .movie button {
    margin-top: 15px;
    cursor: pointer;
  }
</style>
