<template>
  <div class="section3">
    <h2>How it works</h2>
    <p>It's so easy to sell your car with CashForCars!</p>
    <div class="info-block2">
      <div class="icon"></div>
      <h2>1. Enter Your Details</h2>
      <p>It takes just a few minutes to complete a form providing us with details of your vehicle. Answer a few
        questions about your cars mileage, age, condition, etc and fill in your personal details.</p>
    </div>
    <div class="info-block2">
      <h2>1. Enter Your Details</h2>
      <div class="icon">
        <img src="" alt="">
      </div>
      <p>We will contact you within 24hrs. If you are satisfied with our valuation we will arrange for you to meet at
        our premises or for a member of the CashForCars team to visit you.</p>
    </div>
    <div class="info-block2">
      <h2>1. Enter Your Details</h2>
      <div class="icon"></div>
      <p>Once you have met a member of our team the whole process should be concluded within 15–20 minutes. We will
        pay you by draft cheque or transfer the money securely by Faster Payments there and then, with no fees.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Section3',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.section3 {
  height: 760px;
  background: linear-gradient(247.8deg, #126FB8 0%, #252851 100%);
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
