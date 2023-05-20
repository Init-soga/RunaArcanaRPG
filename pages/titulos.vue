<template>
    <v-app class="main">
        <v-container fluid class="container">
            <v-row>
                <v-col style="display: flex; justify-content: center;" cols="6">
                    <img @click="redirectWeller()" class="imagem1" width="75%" :src="require('~/assets/logo1.png')">
                </v-col>
                <v-col style="display: flex; justify-content: center;" cols="6">
                    <img @click="redirectLeo()" class="imagem2" width="75%" :src="require('~/assets/Zefiros/logo.png')">
                </v-col>
            </v-row>
        </v-container>
    </v-app>
</template>

<script>
import 'animate.css';
export default {
    data() {
        return {}
    },
    methods: {
        redirectWeller() {
            this.$router.push({
                path: "/fragmentos"
            })
        },
        redirectLeo() {
            this.$router.push({
                path: "/zefiros"
            })
        }
    }
}
</script>

<style scoped>
.container {
    height: 100vh;
    width: 100vw;
    display: flex;
    text-align: center;
    align-items: center;
}

.imagem2 {
    cursor: pointer;
}

.imagem1 {
    cursor: pointer;
}

.imagem2:hover {
    animation: pulse;
    animation-duration: 1s;
}

.main {
    background-image: url("~/assets/background.png");
}

</style>