<template>
  <div class="n-container">
    <img class="n-img" src="../.././assets/logo.svg" alt="Logo Animals" />

    <div class="n-actions">
      <v-btn color="#6A1990" icon v-for="action in actions" :key="action.id">
        <v-icon size="22">
          {{ action.icon }}
        </v-icon>
      </v-btn>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavbarComp",
  data: () => ({
    actions: [
      { id: 1, icon: "mdi-basket" },
      { id: 2, icon: "mdi-account-circle" },
    ],
  }),
};
</script>

<style scoped>
.n-container {
  display: flex;
  align-items: center;
  justify-content: space-between;

  padding: 15px 25px;

  width: 100%;

  position: absolute;
  top: 0;

  box-shadow: rgba(17, 12, 46, 0.15) 0px 48px 100px 0px;
}

.n-img {
  height: 20px;
}
</style>
