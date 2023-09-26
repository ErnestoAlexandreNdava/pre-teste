<template>
  <div>
    <Header></Header>
    <Banner></Banner>

    <Body></Body>
    <Footer></Footer>
  </div>
</template>

<script>
import Body from '../components/Body.vue'
import Footer from '../components/Footer.vue'
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
export default {
  name: "Master",
  components: {
    Header,
    Banner,
    Footer,
    Body
  },
  data() {
    return {};
  }
};
</script>

<style></style>