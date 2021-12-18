<template>
  <img alt="Jane Design logo" src="./assets/logo.jpeg">
  <div class="center">
    <Button msg="GET STARTED"/>
    <Instagram />
  </div>
</template>

<script>
import Button from './components/Button.vue'
import Instagram from './components/Instagram.vue'

export default {
  name: 'App',
  components: {
    Button,
    Instagram
  }
}
</script>

<style>
#app {
  font-family: 'Karla', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.center {
  margin: auto;
}
</style>
