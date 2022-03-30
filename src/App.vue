<template>
  <MyNavbar/>
  <MyContent/>
</template>

<script>
import MyContent from './components/MyContent.vue'
import MyNavbar from './components/MyNavbar.vue'

export default {
  name: 'App',
  components: {
    MyNavbar,
    MyContent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
* {
  padding: 0;
  margin: 0;
}
</style>
