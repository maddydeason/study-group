<template>
  <section class="main">
    <h1 class="main_heading">Where in the world</h1>
    <world-map></world-map>
  </section>
</template>

<script>
import worldMap from './components/worldMap.vue'

export default {
  name: 'app',
  components: {
    worldMap
  }
}

</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Alegreya|Lato');

.main {
  font-family: 'Lato';
  &_heading {
    font-family: 'Alegreya';
  }
}

</style>
