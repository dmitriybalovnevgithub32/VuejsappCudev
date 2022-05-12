<template>
  <div class="section2">
    <h1>We Pay Cash For Cars</h1>
    <p>CashForCars is the safe, easy and cost effective alternative to selling your car to a dealer or through private
      advertisement. We guarantee to buy your car whatever the make, age, model or condition. No hassle, no time
      wasters, no bouncing cheques and no fees. Sell your car in Belfast today!
      We operate from premises in the Belfast area and will buy cars throughout Northern Ireland.</p>
  </div>
</template>

<script>
export default {
  name: 'Section2',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  align-content: center;
  background: #252851;
}

.section2 {
  margin: 20px 0 20px 0;
  height: 240px;
}
</style>
