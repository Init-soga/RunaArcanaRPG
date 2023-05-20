<template>
  <v-app class="main">
    <v-container fluid class="container">
      <div class="flex-container">
        <div class="titulo1">DESCUBRA E EXPLORE</div>
        <div class="titulo2">RUNETERRA</div>
        <div class="button-container">
          <v-btn class="button" @click="redirect()">Iniciar</v-btn>
        </div>
      </div>
    </v-container>
  </v-app>
</template>

<script>

export default ({
  data() {
    return {

    }
  },
  methods: {
    redirect() {
      this.$router.push({
        path: '/titulos'
      })
    }
  }
})
</script>

<style scoped>
.main {
  background-image: url("~/assets/mapa.jpg");
  background-size: cover;
  background-position: center;
}

.container {
  height: 100vh;
  padding: 0;
}

.flex-container {
  height: 100vh;
  padding: 12px;
  display: flex;
  justify-content: center;
  flex-direction: column;
}

.titulo1 {
  display: flex;
  align-self: center;
  color: gold;
  font-size: 1.5rem;
  font-weight: bold;
}

.titulo2 {
  display: flex;
  align-self: center;
  font-size: 6em;
  letter-spacing: .8rem;
  font-weight: bold;
}

.button {
  font-weight: bold;
  border: 1px solid gold;
  background-color: rgba(0, 0, 0, 0.800);
  padding: 1% 2%;
}

.button-container {
  display: flex;
  justify-content: center;
}

@media screen and (max-width: 480px) {
  .titulo1 {
    font-size: 1em;
  }

  .titulo2 {
    font-size: 2.5em;
  }
}
</style>

<!-- <template>
  <v-app>
    <v-container fluid class="container">
      <v-row class="shadow">
        <v-col cols="12" class="titulo">
          <div style="color: gold;"> DESCUBRA E EXPLORE</div>
          <br>
          <div class="runeterra"> RUNETERRA </div>
        </v-col>
        <v-col cols="12">
          <v-btn @click="redirect()" class="init-button">
            COMEÇAR
          </v-btn>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
export default {
  data() {
    return {}
  },
  methods: {
    redirect() {
      this.$router.push({
        path: '/titulos'
      })
    }
  }
}
</script>

<style scoped>
.container {
  height: 100%;
  width: 100vw;
  display: flex;
  text-align: center;
  align-items: center;
  background-image: url("~/assets/mapa.jpg");
  background-size: cover;
}

.titulo {
  width: 100vw;
  font-size: 1.5rem;
  font-weight: bold;
}

.init-button {
  font-weight: bold;
  border: 1px solid gold;
  background-color: rgba(0, 0, 0, 0.800);
  padding: 1% 2%;
}

.runeterra {
  font-size: 6rem;
  letter-spacing: .8rem;
}

.shadow {
  background: radial-gradient(farthest-side, rgba(1, 10, 19, 0.808), transparent);
} -->

</style>