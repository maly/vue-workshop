<template>
  <div id="app">
  <myButton></myButton>
  <myButton></myButton>
  </div>
</template>

<script>
import myButton from './components/myButton'
export default {
  name: 'app',

  components: {myButton}

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
