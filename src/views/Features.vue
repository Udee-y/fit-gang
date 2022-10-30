<template>
<navbar></navbar>
    <h1 class="py-24">welcome to features page</h1>
    <!-- STANDARD EQUIPMENTS -->
    <!-- COUNTER NUMBER OF SUSCRIBERS -->
    <Footer/>
</template>
<script>
import Navbar from "../components/navbar.vue";
import Footer from "../components/footer.vue";

export default {
  name: "about",
  components: {
    Navbar,
    Footer,
  },
};
</script>