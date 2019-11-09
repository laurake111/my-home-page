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
        background-image: url("assets/taust.jpg");
        background-size: cover;
    }

    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
