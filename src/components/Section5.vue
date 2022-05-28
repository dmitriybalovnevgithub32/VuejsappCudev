<template>
  <div class="section5">
    <div class="block1">
      <div class="card">
        <h1>Trade in</h1>
        <p>Don't let dealers give you less at trade-in, take a look at why CashForCars is a great way to get more
          money
          for your car! There are many great reasons to choose us over a standard dealer trade-in!</p>
      </div>
    </div>
    <div class="block2">
      <div class="card">
        <h1>Trade in</h1>
        <p>Don't let dealers give you less at trade-in, take a look at why CashForCars is a great way to get more
          money
          for your car! There are many great reasons to choose us over a standard dealer trade-in!</p>
      </div>
    </div>
    <div class="block3">
      <h1>What our customers have been saying</h1>
    </div>
    <div class="block4">
      <div class="card">
        <h1>Trade in</h1>
        <p>Don't let dealers give you less at trade-in, take a look at why CashForCars is a great way to get more
          money
          for your car! There are many great reasons to choose us over a standard dealer trade-in!</p>
      </div>
    </div>
    <div class="slider">
      <span class="dots">
        <a class="dot"></a>
        <a class="dot"></a>
        <a class="dot"></a>
        <a class="dot" v-if="con"></a>
      </span>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Section5",
   connect(){ },
}
</script>

<style scoped>

.block1.card {
  background: #126FB8;
  border-radius: 8px;
}

.block2.card {
  background: #126FB8;
  border-radius: 8px;
}

.block3.card {

}

.block4.card {
  background: rgba(18, 111, 184, 0.1);
  border-radius: 8px;
}

.dot-offile {
  width: 12px;
  height: 12px;
  background: rgba(18, 111, 184, 0.1);
}

.dot-active {
  width: 12px;
  height: 12px;
  background: rgba(18, 111, 184, 0.1);
}
</style>
