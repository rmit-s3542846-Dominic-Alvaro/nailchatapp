<template>
  <Chatbox></Chatbox>
</template>

<script>
import Chatbox from '@/components/Chatbox.vue'

export default {
  name: 'app',
  components: {
    Chatbox,
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
  html,body {
  font-family: 'Open Sans', serif;
  font-size: 14px;
  line-height: 1.5;
  height: 100%;
  background-color: #fff;
}
</style>