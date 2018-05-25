<template>
  <div class="hello">
    <h1 class="animated bounceInDown" title="不想和他们一样。">{{ msg }}</h1>
    <ul class="menu">
      <li class="animated bounceInLeft">
        <a
          href="https://github.com/rocwangv"
          target="_blank"
        >
          Github
        </a>
      </li>
      <li class="animated bounceInUp">
        <a
          href="http://blog.rocwong.cn"
          target="_blank"
        >
          Blog
        </a>
      </li>
      <li class="animated bounceInRight">
        <a
          href="http://weibo.com/pengwang2012"
          target="_blank"
        >
          WeiBo
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'Home',
    data () {
      return {
        msg: 'ROC WONG'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: 700;
    letter-spacing: 5px;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }

  a:hover, a:focus {
    background: #42b983;
    color: #ffffff;
  }

  .hello {
    position: absolute;
    top: 50%;
    width: 100%;
    -webkit-transform: translateY(-100%);
    -moz-transform: translateY(-100%);
    -ms-transform: translateY(-100%);
    -o-transform: translateY(-100%);
    transform: translateY(-100%);
  }

  .menu {
    margin-top: 20px;
  }
</style>
