<template>
  <v-main>
    <Navbar />
    <Hero />
    <About />
    <Space />
    <Footer />
  </v-main>
</template>

<script>
import Navbar from "@/components/layouts/Navbar.vue";
import Hero from "@/components/modules/hero/Index.vue";
import About from "@/components/modules/about/Index.vue";
import Space from "@/components/modules/space/Index.vue";
import Footer from "@/components/layouts/Footer.vue";

export default {
  name: "HomeView",
  components: {
    Navbar,
    Hero,
    About,
    Space,
    Footer,
  },
};
</script>
