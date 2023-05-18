<template>
    <v-app class="main">
        <v-row class="titulo-master">
            FRAGMENTOS DE LOUCURA
        </v-row>
        <v-container style="display: flex; justify-content: center; width: 100vw; ">
            <v-card style="margin-top: 2%; " width="90vw">
                <v-row>
                    <v-col cols="12" class="titulo">
                        <div style="display: flex; justify-content: center;"> Campanha </div>
                    </v-col>
                </v-row>
                <div class="texto-campanha">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero numquam autem natus ipsum fuga, a, nobis
                    possimus sapiente saepe illum non ducimus velit, quam laboriosam rerum recusandae reiciendis dolorem
                    voluptates necessitatibus! Recusandae beatae magnam quasi repudiandae magni possimus eum ipsam
                    accusantium dicta rem, sint porro veniam corporis qui minus dolores deleniti quam facilis quod
                    reprehenderit autem iusto doloribus nam praesentium! Commodi sunt dolores cum ex dolore excepturi
                    aliquid repellat minus architecto quas earum, autem exercitationem maiores eius quos nam rem cupiditate
                    aliquam nihil? Magnam repudiandae pariatur cupiditate dicta excepturi debitis officia suscipit odio.
                    Numquam aperiam totam debitis dolore nemo illo, eum iusto quisquam soluta temporibus ipsam quasi optio
                    in velit fuga amet quod dolores dignissimos dolor, voluptatum voluptas! Asperiores maiores
                    necessitatibus saepe nesciunt distinctio error labore maxime. Nemo distinctio voluptatum atque autem
                    fugit, reiciendis odit perspiciatis nisi voluptatem porro amet maxime eligendi, ipsam deleniti eaque,
                    commodi ipsum rem eum libero itaque! Sapiente, culpa consectetur porro quaerat obcaecati fugit
                    consequatur itaque quisquam optio repellendus quas natus tempore officiis voluptatibus odio sit iusto
                    eum nulla mollitia beatae repellat dignissimos! Quibusdam dolor ea id nihil minima tempore accusamus
                    eaque sint. Ea porro autem molestiae consectetur neque sit velit esse placeat, accusantium delectus
                    doloremque illo magnam cumque ipsum, doloribus unde quibusdam repudiandae fuga quam fugiat id aspernatur
                    voluptas. Sunt perspiciatis debitis maxime consequuntur. Dolorem ducimus provident molestias nobis
                    exercitationem, eaque sequi hic quibusdam blanditiis quod velit, magni rerum eveniet cumque sapiente
                    autem temporibus, recusandae ullam. Rerum, eaque atque! Repudiandae, beatae sapiente minima voluptatibus
                    delectus esse omnis! Nemo fugit, modi reiciendis temporibus, officia, voluptas et molestias soluta
                    explicabo tempora dignissimos. Odit qui tenetur illo excepturi, laborum iste, dolorum omnis facilis
                    temporibus, explicabo impedit consectetur voluptate quis illum unde itaque quos est. Aliquam consequatur
                    quam facere accusantium tempore odit, aut repellat! Nobis quasi eius voluptatum nulla vero, veniam iste
                    similique ea reprehenderit nesciunt minima aspernatur, qui facilis atque facere repudiandae, provident
                    est pariatur nisi quisquam? Enim, repudiandae maxime animi magnam asperiores rem assumenda sapiente eius
                    incidunt odio, quibusdam veniam sed facilis rerum voluptatem velit neque ea placeat officia? Voluptatum
                    pariatur, adipisci cupiditate optio, ad distinctio iusto fugiat cumque, unde autem ea voluptas odit
                    eligendi explicabo velit libero facilis minus nemo beatae. Vero fugit esse odit illo voluptatum nostrum
                    nulla perferendis placeat? Sapiente, delectus! Maiores beatae voluptatum facere delectus velit rerum
                    iste quisquam repellendus magnam eius. Ex eius non tempore iure libero omnis, reprehenderit fuga
                    dignissimos voluptatum.
                </div>
            </v-card>
        </v-container>

        <v-container style="display: flex; justify-content: center; width: 100vw; margin-bottom: 2%;">
            <v-card style="margin-top: 2%;" width="90vw">
                <v-row>
                    <v-col cols="12" class="titulo">
                        <div style="display: flex; justify-content: center;"> Personagens </div>
                    </v-col>
                </v-row>
                <div>
                    <v-container>
                        <v-row>
                            <v-col class=" grid-item">
                                <v-row>
                                    <div class="img">
                                        <img style="border-radius: 50%; border: 2px solid gold"
                                            :src="require('~/assets/Fragmentos/qalinna.jpeg')" width="50%;">
                                    </div>
                                </v-row>
                                <v-row style="display: flex; justify-content: center;">
                                    <span class="span-personagem">QALINNA</span>
                                </v-row>
                            </v-col>
                            <v-col class="grid-item">
                                <v-row>
                                    <div class="img">
                                        <img style="border-radius: 50%; border: 2px solid gold"
                                            :src="require('~/assets/Fragmentos/person-placeholder.jpg')" width="50%;">
                                    </div>
                                </v-row>
                                <v-row style="display: flex; justify-content: center;">
                                    <span class="span-personagem">RHODEN</span>
                                </v-row>
                            </v-col>
                            <v-col class="grid-item">
                                <v-row>
                                    <div class="img">
                                        <img style="border-radius: 50%; border: 2px solid gold"
                                            :src="require('~/assets/Fragmentos/person-placeholder.jpg')" width="50%;">
                                    </div>
                                </v-row>
                                <v-row style="display: flex; justify-content: center;">
                                    <span class="span-personagem">KAIOH</span>
                                </v-row>
                            </v-col>
                        </v-row>
                        <v-row>
                            <v-col class="grid-item">
                                <v-row>
                                    <div class="img">
                                        <img style="border-radius: 50%; border: 2px solid gold"
                                            :src="require('~/assets/Fragmentos/person-placeholder.jpg')" width="50%;">
                                    </div>
                                </v-row>
                                <v-row style="display: flex; justify-content: center;">
                                    <span class="span-personagem">MIZO</span>
                                </v-row>
                            </v-col>
                            <v-col class="grid-item">
                                <v-row>
                                    <div class="img">
                                        <img style="border-radius: 50%; border: 2px solid gold"
                                            :src="require('~/assets/Fragmentos/person-placeholder.jpg')" width="50%;">
                                    </div>
                                </v-row>
                                <v-row style="display: flex; justify-content: center;">
                                    <span class="span-personagem">NIVEK</span>
                                </v-row>
                            </v-col>
                            <v-col class="grid-item">
                                <v-row>
                                    <div class="img">
                                        <img style="border-radius: 50%; border: 2px solid gold"
                                            :src="require('~/assets/Fragmentos/person-placeholder.jpg')" width="50%;">
                                    </div>
                                </v-row>
                                <v-row style="display: flex; justify-content: center;">
                                    <span class="span-personagem">ANDRIUS</span>
                                </v-row>
                            </v-col>
                        </v-row>
                        <v-row>
                            <v-col class="grid-item">
                                <v-row>
                                    <div class="img">
                                        <img style="border-radius: 50%; border: 2px solid gold"
                                            :src="require('~/assets/Fragmentos/person-placeholder.jpg')" width="50%;">
                                    </div>
                                </v-row>
                                <v-row style="display: flex; justify-content: center;">
                                    <span class="span-personagem">KHAMZAT</span>
                                </v-row>
                            </v-col>
                            <v-col class="grid-item">

                            </v-col>
                            <v-col class="grid-item">

                            </v-col>
                        </v-row>
                    </v-container>
                </div>
            </v-card>
        </v-container>
    </v-app>
</template>

<script lang="ts">

export default ({
    data() {
        return {}
    }
})
</script>

<style scoped>
.titulo {
    font-size: 1.8rem;
    margin-top: 2%;
    font-weight: bolder;
}

.texto-campanha {
    text-align: justify;
    text-indent: 5%;
    margin: 3%;
    font-weight: bold;
}

.grid-item {
    display: flex;
    justify-content: center;
    flex-direction: column;
    margin: 2%;
}

.img {
    display: flex;
    justify-content: center;
}

.span-personagem {
    text-align: center;
    margin-top: 3%;
    font-weight: bold;
}

.titulo-master {
    font-size: 3rem;
    font-weight: bolder;
    display: flex;
    justify-content: center;
    margin-top: 1%;
}

.main{
    background-image: url("~/assets/background.png");
}
</style>