<template>
  <div id="app">
    <titleComponent msg="La mia prima app con Vue CLI!"/>
  </div>
</template>

<script>
import titleComponent from './components/title.vue'

export default {
  name: 'App',
  components: {
    titleComponent
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
