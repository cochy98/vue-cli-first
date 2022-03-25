<template>
  <div id="app">
    <titleComponent msg="La mia prima app con Vue CLI!"/>
    <heroComponent/>
  </div>
</template>

<script>
import titleComponent from './components/title.vue'
import heroComponent from './components/hero.vue'

export default {
  name: 'App',
  components: {
    titleComponent,
    heroComponent
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
