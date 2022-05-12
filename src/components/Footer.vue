<template>
  <div class="footer">
    <div class="footer-navigation"></div>
    <div class="footer-logo">
      <img src="logo2" alt="toplogo">
    </div>
    <div class="copyrigt">
      <a href="">©2021 Cash for Cars | Terms and Conditions | Privacy Policy</a>
    </div>
  </div>
</template>

<script>
import logo2 from '../assets/logo2.svg';

export default {
  name: "Footer",
  props: {
    msg: String
  },
  data: function () {
    return {
      logo2: logo2
    }
  }
}
</script>

<style scoped>

</style>
