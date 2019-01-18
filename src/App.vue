<template>
  <div id="app">
    <HelloWorld msg="Rajendra Shenoy"/>
    <HelloExperience msg="Rajendra Shenoy"/>
    <HelloCopy msg="Rajendra Shenoy"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloExperience from './components/HelloExperience.vue'
import HelloCopy from './components/HelloCopy.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,HelloExperience,HelloCopy
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
