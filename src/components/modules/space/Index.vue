<template>
  <div class="s-main">
    <v-container class="s-container">
      <div class="s-container__section-actions">
        <div class="s-container__texts">
          <div class="s-container__text-indicator">
            <span>nosso espaço</span>
            <div class="s-text__indicator"></div>
          </div>

          <h2>Sobre o nosso espaço... É perfeito!</h2>

          <span>
            São mais de 500m² de área verde, brinquedos e muito mais!
          </span>
        </div>
      </div>

      <img
        class="s-img__dog"
        src="../../.././assets/vector-space-dog-happy.svg"
        alt="Vetor com cachorro correndo"
      />

      <div class="s-container__footer">
        <span>
          Os pets são separados por turmas e monitorados por nossos instrutores.
        </span>

        <a href="#"> Clique aqui e saiba mais sobre nossa equipe </a>
      </div>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "SpaceComp",
};
</script>

<style scoped>
.s-main {
  height: 100vh;
  background: #fff0f6;
}

.s-container {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;

  height: 100%;
}

.s-container__texts {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.s-container__text-indicator {
  display: flex;
  align-items: center;
  flex-direction: column;

  margin: 25px;
}

.s-container__text-indicator > span {
  font-size: 22px;
}

.s-text__indicator {
  width: 55px;
  height: 4px;
  border-radius: 25px;

  background: #ed2e7c;
}

.s-container__texts > h2 {
  text-align: center;
  font-size: 46px;
  color: #ed2e7c;
  width: 950px;
  margin: 10px 0;
}

.s-container__texts > span {
  text-align: center;
  font-size: 18px;
  color: #000000;
  width: 1200px;
  margin: 10px 0;
}

.s-container__imgs {
  margin: 30px 0;
}

.s-img__dog {
  height: 350px;
  margin: 30px 0;
}

.s-container__footer {
  display: flex;
  flex-direction: column;
}

.s-container__footer > span {
  text-align: center;
  font-size: 18px;
  margin: 0 0 15px 0;
}

.s-container__footer > a {
  text-align: center;
  font-size: 18px;
  color: #ed2e7c;
}
</style>
