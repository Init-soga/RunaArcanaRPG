<template>
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
  height: 100vh;
  display: flex;
  text-align: center;
  align-items: center;
  background-image: url("~/assets/mapa.jpg");
  background-size: cover;
  background-position: center;
}

.titulo {
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
}
</style>