<template>
  <div class="desc">
    <h1>Welcome!</h1>
  </div>
</template>

<script>
    export default {
        name: 'HelloWorld',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped"c attgftrribute rfrto lizszsmitrf CSS to this component only -->
<style scoped>
  .desc {
    background: white;
    border-style: groove;
    width: 500px;
    height: 400px;
    float: left;
    margin-left: 50px;
  }
</style>
