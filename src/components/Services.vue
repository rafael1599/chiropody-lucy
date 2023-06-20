
<template>
  <div class="services">
    <h1>SERVICIO PODOLÓGICO ESPECIALIZADOS</h1>
    <div class="cards">
      <div class="services__card card">
        <v-card class="mx-auto" max-width="344">
          <v-img src="../assets/img/services.svg" height="200px" cover></v-img>
          <v-card-title> Servicios podolgicos </v-card-title>
          <v-card-subtitle> Nuestra especialidad 1</v-card-subtitle>
          <v-card-actions>
            <!-- <v-btn color="orange-lighten-2" variant="text"> Saber mas </v-btn>
            <v-spacer></v-spacer> -->
            <v-btn :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'" @click="show = !show"></v-btn>
          </v-card-actions>
          <v-expand-transition>
            <div v-show="show">
              <v-divider></v-divider>
              <v-card-text>
                <p>Podologia preventiva</p>
                <p>Podologia geriátrica</p>
                <p>Podología pediátrica</p>
                <p style="color: white;">Podologia y tratamiento</p>
                <p style="color: white;">Podologia y tratamiento</p>
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </div>
      <div class="treatment__card card">
        <v-card class="mx-auto" max-width="344">
          <v-img src="../assets/img/tratamientos.svg" height="200px" cover></v-img>
          <v-card-title> Tratamientos </v-card-title>
          <v-card-subtitle> Nuestra especialidad 2</v-card-subtitle>
          <v-card-actions>
            <!-- <v-btn color="orange-lighten-2" variant="text"> Saber mas </v-btn>
            <v-spacer></v-spacer> -->
            <v-btn :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'" @click="show = !show"></v-btn>
          </v-card-actions>
          <v-expand-transition>
            <div v-show="show">
              <v-divider></v-divider>
              <v-card-text>
                <p>Pie de atleta</p>
                <p>Hongos en uñas</p>
                <p>Curación de pies diabético</p>
                <p>Desbritacion de callos</p>
                <p>Uñas encarnadas</p>
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </div>

      <div class="package__card card">
        <v-card class="mx-auto" max-width="344">
          <v-img src="../assets/img/paquete.svg" height="200px" cover></v-img>
          <v-card-title> Paquete completo </v-card-title>
          <v-card-subtitle> Nuestra especialidad 3</v-card-subtitle>
          <v-card-actions>
            <!-- <v-btn color="orange-lighten-2" variant="text"> Saber mas </v-btn>
            <v-spacer></v-spacer> -->
            <v-btn :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'" @click="show = !show"></v-btn>
          </v-card-actions>
          <v-expand-transition>
            <div v-show="show">
              <v-divider></v-divider>
              <v-card-text>
                <p>Podologia y reflexologia podal</p>
                <p>Podologia y uña encarnada</p>
                <p>Podologia y tratamiento</p>
                <p style="color: white;">Podologia y tratamiento</p>
                <p style="color: white;">Podologia y tratamiento</p>
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Services',
  props: {
    msg: String

  },
  data: () => ({
    show: false,
  }),
}


</script>
