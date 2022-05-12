<template>
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
        <img src="logo3" alt="img-img">
      </div>
    </div>
  </div>
</template>

<script>
import logo3 from '../assets/logo2.svg';

export default {
  name: "Section4",
  props: {
    msg: String
  },
  data: function () {
    return {
      logo3: logo3
    }
  }
}

</script>

<style scoped>

</style>
