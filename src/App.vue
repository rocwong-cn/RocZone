<template>
  <div id="app">
    <router-view/>
    <a href="http://www.miitbeian.gov.cn/" target="_blank"><p class="bei-an">京ICP备18022839号</p></a>
  </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    width: 100%;
    overflow: hidden;
  }

  .bei-an {
    color: #666;
    font-size: 12px;
    position: absolute;
    bottom: 0;
    width: 100%;
  }
</style>
