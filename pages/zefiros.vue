<template>
    <v-app class="main">
        <div class="main-title">
            ZÉFIROS DE ARDOR
        </div>
        <div class="card">
            <span class="titulo-campanha">CAMPANHA</span>
            <span class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum aut non sit labore, a ex
                architecto
                quasi modi, at illo natus ut numquam provident vitae commodi earum soluta placeat aperiam!</span>
        </div>
        <div class="card">
            <span class="titulo-campanha">PERSONAGENS</span>
            <v-container class="container-personagens">
                <v-row>
                    <v-col cols="12" sm="4">
                        <div class="col-personagem">
                            <img class="imagem" :src="require('~/assets/Zefiros/RUHRA.jpg')" width="50%;">
                        </div>
                        <div class="personagem-text">RUHRA</div>
                    </v-col>
                    <v-col cols="12" sm="4">
                        <div class="col-personagem">
                            <img class="imagem" :src="require('~/assets/Zefiros/SPLASH-1.jpg')" width="50%;">
                        </div>
                        <div class="personagem-text">PUKAVY</div>
                    </v-col>
                    <v-col cols="12" sm="4">
                        <div class="col-personagem">
                            <img class="imagem" :src="require('~/assets/Zefiros/SPLASH-2.jpg')" width="50%;">
                        </div>
                        <div class="personagem-text">RICO</div>
                    </v-col>
                    <v-col cols="12" sm="4">
                        <div class="col-personagem">
                            <img class="imagem" :src="require('~/assets/Zefiros/SPLASH-3.jpg')" width="50%;">
                        </div>
                        <div class="personagem-text">RURIC THAR</div>
                    </v-col>
                    <v-col cols="12" sm="4">
                        <div class="col-personagem">
                            <img class="imagem" :src="require('~/assets/Zefiros/SPLASH-4.jpg')" width="50%;">
                        </div>
                        <div class="personagem-text">TORI</div>
                    </v-col>
                    <v-col cols="12" sm="4">
                        <div class="col-personagem">
                            <img class="imagem" :src="require('~/assets/Zefiros/SPLASH.jpg')" width="50%;">
                        </div>
                        <div class="personagem-text">ATLAS</div>
                    </v-col>
                </v-row>
            </v-container>
        </div>
    </v-app>
</template>

<script lang="ts">

export default ({
    data() {
        return {
            splash1: require('~/assets/Fragmentos/person-placeholder.jpg'),
            splashQalinna: require('~/assets/Fragmentos/qalinna.jpeg')
        }
    }
})
</script>

<style scoped>
.main {
    background-image: url("~/assets/background.png");
}

.main-title {
    display: flex;
    justify-content: center;
    margin: 5%;
    font-size: 1.8em;
    text-align: center;
    font-weight: bold;
}

.card {
    margin: 7%;
    display: flex;
    flex-direction: column;
    border: 1px solid gold;
    border-radius: 5px;
    background-color: rgba(0, 0, 0, 0.300);
}

.titulo-campanha {
    font-size: 1.4em;
    font-weight: bold;
    display: flex;
    justify-content: center;
    margin: 3%;
}

.text {
    font-weight: bold;
    font-style: italic;
    text-indent: 5%;
    text-align: justify;
    margin: 5%;
    font-size: 16px;
}


.col-personagem {
    display: flex;
    justify-content: center;
    margin: 2%;
    ;
}

.imagem {
    border-radius: 50%;
    border: 2px solid gold;
}

.personagem-text {
    display: flex;
    justify-content: center;
    margin-top: 2%;
    margin-bottom: 2%;
    font-weight: bold;
    font-size: 1.2em;
}

/* Dekstop view*/
@media screen and (min-width: 600px) {
    .card {
        margin: 1%;
    }

    .main-title {
        margin: 2%;
    }
}
</style>