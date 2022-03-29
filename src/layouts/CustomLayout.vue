<template>
  <div class="relative">
    <!-- nav -->
    <Navbar></Navbar>
    <!-- main -->

    <slot />   
    <!-- Footer -->
    <Footer></Footer>
  </div>
</template>

<script>
import Navbar from "../components/Navigation/Navbar.vue";
import Footer from "../components/Navigation/Footer.vue";
import Test from "../components/Navigation/Test.vue";
export default {
  components: {
    Navbar,
    Footer,
    Test,
  },
};
</script>

<style>
</style>