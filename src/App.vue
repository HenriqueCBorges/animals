<template>
  <v-app>
    <HomeView />
  </v-app>
</template>

<script>
import HomeView from "@/views/Home.vue";

export default {
  name: "App",

  components: {
    HomeView,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
* {
  font-family: "Poppins";
}
</style>
