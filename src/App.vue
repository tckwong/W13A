<template>
  <div id="app">
    <AppHeader></AppHeader>
    <AppBody></AppBody>
    <AppFooter></AppFooter>
  </div>
</template>

<script>
import AppHeader from './components/appheader.vue'
import AppBody from './components/appbody.vue'
import AppFooter from './components/appfooter.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppBody,
    AppFooter
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
</style>
