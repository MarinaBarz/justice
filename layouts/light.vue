<template>
  <div>
    <Header class-name="black"/>
    <nuxt/>
    <Footer/>
  </div>
</template>

<script>
import Footer from "~/components/Footer.vue";
import Header from "~/components/Header.vue";
export default {
  components: {
    Footer,
    Header
  }
};
</script>
