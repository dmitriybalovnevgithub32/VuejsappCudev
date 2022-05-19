<template>
  <header>
    <a href="/" class="logo">
      <img src="logo1" alt="toplogo">
    </a>
    <ul>
      <li><a href="">How it works</a></li>
      <li><a href="">Why choose us</a></li>
      <li><a href="">FAQs</a></li>
      <li><a href="">Contact</a></li>
    </ul>
    <div class="btns">
      <a href="#" class="btn_light">Sign In</a>
      <a href="#" class="btn_green"> Join The Movement</a>
    </div>
  </header>
</template>

<script>
import logo1 from '../assets/logo2.svg';

export default {
  name: 'Header',
  props: {
    msg: String
  },
  data: function () {
    return {
      logo1: logo1
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  align-content: space-between;
  background: #252851;
  height: 104px;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111111;
}

h3 {
  margin: 40px 0 0;
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
</style>
