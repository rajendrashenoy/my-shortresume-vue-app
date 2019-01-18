<template>
  <div class="hello">
    <p>This application is powered by vue.js, &copy 2019 Rajendra Shenoy</p>
  </div>
</template>

<script>
export default {
  name: 'HelloCopy',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.hello{
position: fixed;
bottom: 1%;
left: 1%;
height:10%;
width:100%;
overflow-y: scroll;
font-size:small;
}


</style>
