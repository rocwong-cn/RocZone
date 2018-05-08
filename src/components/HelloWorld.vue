<template>
  <div class="hello">
    <h2 class="animated bounceInDown">{{ msg }}</h2>
    <ul>
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
          href="http://rocwang.cc"
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
    name: 'HelloWorld',
    data () {
      return {
        msg: 'Welcome to Roc\'s zone !'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
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
    text-decoration: none;
  }

  .hello {
    position: absolute;
    top: 40%;
    width: 100%;
  }
</style>
