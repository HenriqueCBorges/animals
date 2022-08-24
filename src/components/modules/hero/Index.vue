<template>
  <div class="h-main">
    <v-container class="h-container">
      <div class="h-container__section-actions">
        <div class="h-container__texts">
          <span>Carinho, amor e atenção</span>
          <h1>Cuidamos do seu pet do jeito que ele merece</h1>
          <h4>Os melhores cuidados para o seu melhor amigo.</h4>
        </div>

        <div class="h-container__actions">
          <v-btn
            class="mr-3 rounded-lg"
            color="#ED2E7C"
            height="50px"
            outlined
            depressed
          >
            SAIBA MAIS
          </v-btn>

          <v-btn
            class="rounded-lg"
            color="#ED2E7C"
            height="50px"
            dark
            depressed
          >
            ENTRAR EM CONTATO
          </v-btn>
        </div>
      </div>

      <img
        class="n-img"
        src="../../.././assets/vector-hero.svg"
        alt="Logo Animals"
      />
    </v-container>
  </div>
</template>

<script>
export default {
  name: "HeroComp",
};
</script>

<style scoped>
.h-main {
  height: 100vh;
  background: #ffdbea;
}

.h-container {
  display: flex;
  align-items: center;
  justify-content: space-between;

  height: 100%;
}

.h-container__texts > span {
  font-size: 18px;
  color: #ed2e7c;
}

.h-container__texts > h1 {
  font-size: 66px;
  color: #6a1990;
  width: 950px;
  margin: 10px 0;
}

.h-container__texts > h4 {
  font-size: 28px;
  font-weight: 400;
  color: #000000;
  width: 950px;
  margin: 10px 0;
}

.h-container__actions {
  margin: 40px 0 0 0;
}
</style>
