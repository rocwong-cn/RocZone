<template>
  <div id="app">
    <router-view/>
    <div class="footer">
      <div class="license">
        <span>©{{y}}&nbsp;RocWong</span>
        <span> | </span>
        <a href="http://www.miitbeian.gov.cn/" target="_blank"><span>京ICP备18022839号</span></a>
      </div>
      <svg class="editorial" xmlns="http://www.w3.org/2000/svg"
           xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 24 150 28" preserveAspectRatio="none">
        <defs>
          <path id="gentle-wave" d="M-160 44c30 0
                                        58-18 88-18s
                                        58 18 88 18
                                        58-18 88-18
                                        58 18 88 18
                                        v44h-352z"></path>
        </defs>
        <g class="parallax">
          <use xlink:href="#gentle-wave" x="50" y="0" fill="rgba(128,215,175,.5)"></use>
          <use xlink:href="#gentle-wave" x="50" y="3" fill="rgba(128,215,175,.5)"></use>
          <use xlink:href="#gentle-wave" x="50" y="6" fill="rgba(128,215,175,.5)"></use>
        </g>
      </svg>
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
