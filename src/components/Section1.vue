<template>
  <div class="section1">
    <div class="left">
      <h1>Enter your vehicle details to receive a free vluation.</h1>
      <p>if your vehicle and contact details and we will contact you with a cash valuation within 24 hours.</p>
    </div>
    <div class="right">
      <div class="enter-reg">
        <a href="" class="enter-reg">ENTER REG</a>
      </div>
      <div class="checkbox">
        <input type="checkbox">
        <p>I confirm that the vehicle I am enquiring about has less than 100,000 miles.</p>
        <a href="">Get Started span <span class="icon-ghjk">
          <svg width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path
                d="M2.5 10C2.5 5.59 6.09 2 10.5 2C14.91 2 18.5 5.59 18.5 10C18.5 14.41 14.91 18 10.5 18C6.09 18 2.5 14.41 2.5 10ZM0.5 10C0.499999 15.52 4.98 20 10.5 20C16.02 20 20.5 15.52 20.5 10C20.5 4.48 16.02 -1.95827e-07 10.5 -4.37114e-07C4.98 -6.78401e-07 0.5 4.48 0.5 10ZM10.5 9L7.5 9C6.95 9 6.5 9.45 6.5 10C6.5 10.55 6.95 11 7.5 11L10.5 11L10.5 12.79C10.5 13.24 11.04 13.46 11.35 13.14L14.14 10.35C14.34 10.15 14.34 9.84 14.14 9.64L11.35 6.85C11.04 6.54 10.5 6.76 10.5 7.21L10.5 9Z"
                fill="#252851"/>
          </svg>
        </span>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
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

.header {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  align-content: center;
  background: #252851;
}

.icon-ghjk {  }

h1 {
  color: #126FB8;
}

p {
  color: #252851;
}
</style>
