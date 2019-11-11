<template>
  <div id="app">
    <HelloWorld/>
  </div>
</template>

<script>
    import HelloWorld from './components/Description.vue'

    export default {
        name: 'app',
        components: {
            HelloWorld
        }
    }
</script>

<style>
  body {
    background-image: url("../taust.jpg");
    background-size: cover;
  }

  #app {
    font-family: Rockwell;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: darkslateblue;
    margin-top: 60px;
  }
</style>
