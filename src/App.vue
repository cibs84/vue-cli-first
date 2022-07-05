<template>
  <div id="app">
    <MyTitle/>
    <MyJumbotron/>
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import MyJumbotron from './components/MyJumbotron.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    MyJumbotron
  }
}
</script>

<style lang="scss">
// RESET
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
// APP
#app {
  font-family: Helvetica, sans-serif;
}
</style>
