<template>
  <div class="block-with-list">
    <div class="left">
      <ul>
        <li><a href="">Sell your car right away </a></li>
        <li><a href="">Secure payment & release of ownership</a></li>
        <li><a href="">Sales are final</a></li>
        <li><a href="">Instant Payment</a></li>
        <li><a href="">No Fees</a></li>
        <li><a href="">No Strangers Visiting Your Home</a></li>
        <li><a href="">No Time Wasters & Tyre Kickers</a></li>
        <li><a href="">We'll take your car as it is</a></li>
      </ul>
    </div>
    <div class="righ">
      <ul>
        <li><a href="">We'll take your car as it is</a></li>
        <li><a href="">Cash in hand and more of it</a></li>
        <li><a href="">Transparent and fair appraisal</a></li>
        <li><a href="">Know the price upfront</a></li>
        <li><a href="">Easy and convenient</a></li>
        <li><a href="">Outstanding Finance Settled</a></li>
        <li><a href="">No Bouncing Cheques</a></li>
        <li><a href="">Avoid Uninsured Test Drives</a></li>
      </ul>
    </div>

  </div>
</template>

<script>
import icon from '../assets/icons/icon.svg';

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Section1',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.section1 {
  height: 720px;
}

.block-with-list ul li a {
  opacity: 1;
  color: #252851;
  font-style: Manrope;
  font-weight: 700;
  font-size: 16px;
  Line-height: 24px;

}

.block-with-list {
  max-width: 1024px;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: space-evenly;
  align-items: center;
  align-content: stretch;
  margin: 0 auto;
  background: rgba(232, 241, 248 0.1);
  border-radius: 8px;
}

.header {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  align-content: center;
  background: #252851;
}

h1 {
  color: #126FB8;
}

ul li a {
  text-decoration: none;
  margin: 4px;
  padding: 4px;
  margin-bottom: 10px;
}

ul li {
  list-style: url('../assets/icons/icon.svg');
  text-align: left;
}

p {
  color: #252851;
}
</style>
