<template>

  <Header/>
  <Section1/>
  <Section2/>
  <Section3/>
  <Section4/>
  <Section5/>
  <Section8/>
  <Section6/>
  <Section7/>
  <Footer/>

</template>

<script>

import Header from "@/components/Header";
import Section1 from "@/components/Section1";
import Section2 from "@/components/Section2";
import Section3 from "@/components/Section3";
import Section4 from "@/components/Section4";
import Section5 from "@/components/Section5";
import Section6 from "@/components/Section6";
import Section7 from "@/components/Section7";
import Section8 from "@/components/Section8";
import Footer from "@/components/Footer";

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Section7,
    Section8,
    Section6,
    Section5,
    Section4,
    Section3,
    Section2,
    Section1
  }
}
</script>

<style>

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
  margin-top: 0px;
}
</style>
