<template>
  <div id="app">
    <Personajes/>
  </div>
</template>

<script>
import Personajes from './components/Personajes.vue'

export default {
  name: 'App',
  components: {
    Personajes
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  background-image: url('https://rickandmortypod.com/wp-content/uploads/2018/11/cropped-RM_page-header_background1-3.png');
  height: 1000px;
}
</style>
