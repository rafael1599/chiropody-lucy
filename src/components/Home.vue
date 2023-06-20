<template>
  <div class="home">
    <div class="desc">
      <div class="logos">
        <div class="img">
          <img src="../assets/logo.svg">
        </div>
        <div class="social">
          <img src="../assets/f.svg" alt="facebook">
          <img src="../assets/w.svg" alt="whatsapp">
          <img src="../assets/i.svg" alt="ig">
          <img src="../assets/m.svg" alt="email">
        </div>
      </div>
      <div class="text">
        <h1>SERVICIO PODOLÓGICO ESPECIALIZADOS Y TERAPIAS REHABILITADORAS</h1>
        <p>¡Cuida tus pies, regala bienestar! Con nuestros servicios podológicos especializados y terapias
          rehabilitadoras, caminarás hacia una vida más saludable.</p>
      </div>
    </div>
    <div class="landing__img">
      <img src="../assets/podiatry-landing.jpg">
    </div>
  </div>
  <div class="services">
    <div class="services__cards">
      <v-card class="mx-auto services__card" max-width="344">
        <v-img src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg" height="200px" cover></v-img>

        <v-card-title> Top western road trips </v-card-title>

        <v-card-subtitle> 1,000 miles of wonder </v-card-subtitle>

        <v-card-actions>
          <v-btn color="orange-lighten-2" variant="text"> Explore </v-btn>

          <v-spacer></v-spacer>

          <v-btn :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'" @click="show = !show"></v-btn>
        </v-card-actions>

        <v-expand-transition>
          <div v-show="show">
            <v-divider></v-divider>

            <v-card-text>
              I'm a thing. But, like most politicians, he promised more than he
              could deliver. You won't have time for sleeping, soldier, not with all
              the bed making you'll be doing. Then we'll go with that data file!
              Hey, you add a one and two zeros to that or we walk! You're going to
              do his laundry? I've got to find a way to escape.
            </v-card-text>
          </div>
        </v-expand-transition>
      </v-card>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String
    
  },
  data: () => ({
    show: false,
  }),
}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.social img {
  margin-left: 10px;
}

.logos {
  display: flex;
  justify-content: space-around;
}

.home {
  display: flex;
  padding: 0 50px 0 50px;
}

.desc {
  padding-right: 50px;
}

.landing__img {
  padding: 0 30px 0;
}

.text h1 {
  @import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&family=Roboto:wght@300&display=swap');
  font-family: 'Roboto', sans-serif;
  font-size: 40px;

}

.text p {
  font-family: 'Josefin Sans', sans-serif;
  font-size: 32px;
}
</style>
