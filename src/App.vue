<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>

  export default {
    name: 'App',
    data () {
      return {
        test: 'test',
      }
    }
  }
</script>

<style lang="scss">
#app {
  font-family: Roboto, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background: linear-gradient(180deg, #edfdf4 0%, #FFFFFF 100%);
  height: 80vh;
  text-align: center;
  text-align: -webkit-center;
  text-align: -moz-center;
}

</style>
