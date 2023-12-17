<template>
  <!-- calling form -->
<SignUp/>
</template>

<script>
// importing form
import SignUp from './components/SignUp.vue'
export default {
  name: 'App',
  components: {
    SignUp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body{
  margin: 0px;
  background: #696969;
  
}

*{
  color: rgb(84, 161, 228);
}
</style>
