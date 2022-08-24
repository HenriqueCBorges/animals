<template>
  <div class="a-main">
    <v-container class="a-container">
      <div class="a-container__section-actions">
        <div class="a-container__texts">
          <div class="a-container__text-indicator">
            <span>quem somos</span>
            <div class="a-text__indicator"></div>
          </div>

          <h2>
            Temos como missão entregar o melhor atendimento para o seu bichinho.
          </h2>

          <span
            >São mais de 10 anos entregando um trabalho que visa apenas o melhor
            para o seu pet, pois sabemos que não existe nada mais precioso nesse
            mundo que ver o seu melhor amigo sendo tratado como “princeso(a)”
            que ele é.
          </span>
        </div>
      </div>

      <div class="a-container__imgs">
        <img
          class="a-img__dogs"
          src="../../.././assets/vector-about-dogs.svg"
          alt="Vetor com cachorros"
        />

        <img
          class="a-img__cat"
          src="../../.././assets/vector-about-cat.svg"
          alt="Vetor com gato"
        />
      </div>

      <div class="a-container__footer">
        <span> A felicidade deles é o que nos motiva a continuar. 💜 </span>
      </div>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "AboutComp",
};
</script>

<style scoped>
.a-main {
  height: 100vh;
  background: #ffffff;
}

.a-container {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;

  height: 100%;
}

.a-container__texts {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.a-container__text-indicator {
  display: flex;
  align-items: center;
  flex-direction: column;

  margin: 25px;
}

.a-container__text-indicator > span {
  font-size: 22px;
}

.a-text__indicator {
  width: 55px;
  height: 4px;
  border-radius: 25px;

  background: #ed2e7c;
}

.a-container__texts > h2 {
  text-align: center;
  font-size: 46px;
  color: #ed2e7c;
  width: 950px;
  margin: 10px 0;
}

.a-container__texts > span {
  text-align: center;
  font-size: 18px;
  color: #000000;
  width: 1200px;
  margin: 10px 0;
}

.a-container__imgs {
  margin: 30px 0;
}

.a-container__imgs > img {
  height: 250px;
  margin: 0 10px;
}
</style>
