<template>
  <div>
    <Sidebar />
    <Navbar />
    <slot name="content" />

    <Configurator />
    <Footer />
  </div>
</template>

<script>
import Navbar from "@/Components/Main/Navbar.vue";
import Sidebar from "@/Components/Main/Sidebar.vue";
import Footer from "@/Components/Main/Footer.vue";
import Configurator from "@/Components/Main/Configurator.vue";

export default {
  components: {
    Navbar,
    Sidebar,
    Configurator,
    Footer,
  },
};




</script>

<style lang="css" >

  .async-hide {
        opacity: 0 !important
    }
</style>
