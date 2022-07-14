<template>
  <div id="app">
    <HeroComponent/>
  </div>
</template>

<script>
import HeroComponent from './components/HeroContent.vue'

export default {
  name: 'App',
  components: {
    HeroComponent,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
