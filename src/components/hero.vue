<template>
  <div class="jumbotron">
    <div class="jumbo-image">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRxScpxltw4pkeUqxDq-WtFW6swTGmgAkDUzA&usqp=CAU" alt="Vue CLI logo">
    </div>
    <div class="jumbo-description">
      <h1>Questo è un jumbotron</h1>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum aspernatur accusantium consequuntur eum cupiditate ipsam a animi! Necessitatibus ea dicta rem molestiae corrupti nostrum quod nemo, blanditiis, nihil pariatur consectetur.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'heroComponent',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div.jumbotron{
  display: flex;
  width: 100%;
  height: 500px;
  background-color: rgba(250, 66, 66, 0.507);
}

div.jumbotron > .jumbo-image,
div.jumbotron > .jumbo-description{
  flex-basis: 50%;
  height: 100%;
}

.jumbo-image > img{
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.jumbo-description{
	display: flex;
	flex-direction: column;
	justify-content: center;
}
</style>
