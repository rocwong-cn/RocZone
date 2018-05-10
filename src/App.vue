<template>
  <div id="app">
    <router-view/>
    <div class="footer">
      <span>©{{y}} RocWong</span>
      <span> | </span>
      <a href="http://www.miitbeian.gov.cn/" target="_blank"><span>京ICP备18022839号</span></a>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'App',
    data(){
      return { y: new Date().getFullYear() }
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
    width: 100%;
    overflow: hidden;
  }

  .footer {
    position: absolute;
    bottom: 10px;
    width: 100%;
    color: #666;
    font-size: 12px;
  }

  .footer a, .footer a:visited, .footer a:hover {
    color: #666;

  }

</style>
