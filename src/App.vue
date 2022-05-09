<template>
  <div class="header">
    <div class="logo">
      <img src="./assets/logo2.svg" alt="toplogo">
    </div>
    <div class="navigation">
      <ul>
        <li><a href="">How it works</a></li>
        <li><a href="">Why choose us</a></li>
        <li><a href="">FAQs</a></li>
        <li><a href="">Contact</a></li>
      </ul>
    </div>
  </div>

  <div class="section1">
    <div class="left">
      <h1>Enter your vehicle details to receive a free vluation.</h1>
      <p>if your vehicle and contact details and we will contact you with a cash valuation within 24 hours.</p>
    </div>
    <div class="right">
      <div class="enter-reg"></div>
      <div class="checkbox">
        <input type="checkbox">
        <p>I confirm that the vehicle I am enquiring about has less than 100,000 miles.</p>
        <input type="button" value="Get Started">
      </div>
    </div>
  </div>
  <div class="section2">
    <h1>We Pay Cash For Cars</h1>
    <p>CashForCars is the safe, easy and cost effective alternative to selling your car to a dealer or through private
      advertisement. We guarantee to buy your car whatever the make, age, model or condition. No hassle, no time
      wasters, no bouncing cheques and no fees. Sell your car in Belfast today!
      We operate from premises in the Belfast area and will buy cars throughout Northern Ireland.</p>
  </div>
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
  <div class="section4">
    <h1>Why choose CashForCars to sell your car?</h1>
    <div class="left">
      <p>Advertising your car for sale privately can be a costly, not to mention frustrating process which is renowned
        for attracting time wasters.

        Using CashForCars eliminates the hassle of strangers visiting your home, the worry associated with them
        taking a test drive uninsured and guarantees peace of mind by working with a reputable company.

        By dealing directly with CashForCars you also eliminate the worry of cheques bouncing and unsatisfied
        customers returning to your door.

        CashForCars is the quick, easy and efficient way to turn your car into cash for whatever reason. If you are
        purchasing a replacement vehicle of a dealer, selling your car to CashForCars puts you in the driving seat
        and you will be able to negotiate a much better deal.</p>
    </div>
    <div class="right">
      <div class="img">
        <img src="./assets/img.svg" alt="img-img">
      </div>
    </div>
  </div>
  <div class="section5">
    <div class="block">
      <div class="card">
        <h1>Trade in</h1>
        <p>Don't let dealers give you less at trade-in, take a look at why CashForCars is a great way to get more
          money
          for your car! There are many great reasons to choose us over a standard dealer trade-in!</p>
      </div>
    </div>
    <div class="block">
      <div class="card">
        <h1>Trade in</h1>
        <p>Don't let dealers give you less at trade-in, take a look at why CashForCars is a great way to get more
          money
          for your car! There are many great reasons to choose us over a standard dealer trade-in!</p>
      </div>
    </div>
    <div class="block">
      <h1>What our customers have been saying</h1>
    </div>
    <div class="block">
      <div class="card">
        <h1>Trade in</h1>
        <p>Don't let dealers give you less at trade-in, take a look at why CashForCars is a great way to get more
          money
          for your car! There are many great reasons to choose us over a standard dealer trade-in!</p>
      </div>
    </div>
  </div>
  <div class="section6">
    <h1>Receive your free valuation now</h1>
    <div class="button">
      <a href="" class="get-started"></a>
    </div>
  </div>
  <div class="section7">
    <h1>Receive your free valuation now</h1>
    <div class="button">
      <a href="" class="get-started"></a>
    </div>
  </div>

  <div class="footer">
    <div class="footer-navigation"></div>
    <div class="footer-logo">
      <img src="./assets/logo2.svg" alt="toplogo">
    </div>
    <div class="copyrigt">
      <a href="">©2021 Cash for Cars | Terms and Conditions | Privacy Policy</a>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
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

.section1 {
  background: linear-gradient(79.95deg, rgba(18, 111, 184, 0.2) 2.62%, rgba(18, 111, 184, 0) 98.24%);
}
.footer {
  height: 184px;
  background: #252851;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
