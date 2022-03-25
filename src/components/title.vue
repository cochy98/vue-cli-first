<template>
  <div class="title">
    <h2>{{ msg }}</h2>
  </div>
</template>

<script>
export default {
  name: 'titleComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div.title > h2{
  text-align: center;
  padding: 2rem;
}
</style>
