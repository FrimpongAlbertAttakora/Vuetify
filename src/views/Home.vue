<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <appToolbar msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import appToolbar from '../components/appToolbar.vue'

export default {
  name: 'home',
  components: {
    appToolbar
  }
}
</script>
