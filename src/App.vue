<template>
  <div id="app">
    <container></container>
  </div>
</template>

<script>
import Container from '@/components/Container.vue'

export default {
  name: 'app',
  components: {
    Container
  }
}
</script>

<style>
body {
  margin: 0px;
  padding: 0px;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  padding: 0px;
  margin: 0px;
}
</style>
