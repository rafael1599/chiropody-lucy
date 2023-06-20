<template>
<div class="laser__treatments">
    <h1 class="text">TERAPIAS REHABILITADORAS</h1>
    <div class="cards">
      <div class="laser__card card">
        <v-card class="mx-auto" max-width="344">
          <v-img src="../assets/img/terapia1.svg" height="200px" cover></v-img>
          <v-card-title> Terapia de masaje podologico</v-card-title>
          <v-card-title> ...</v-card-title>
        </v-card>
      </div>
      <div class="laser__card card">
        <v-card class="mx-auto" max-width="344">
          <v-img src="../assets/img/terapia2.svg" height="200px" cover></v-img>
          <v-card-title> Terapia de electroestimulacion</v-card-title>
          <v-card-title> Terapia de masaje podologico</v-card-title>
        </v-card>
      </div>
      <div class="laser__card card">
        <v-card class="mx-auto" max-width="344">
          <v-img src="../assets/img/terapia3.svg" height="200px" cover></v-img>
          <v-card-title> Terapia con vendaje</v-card-title>
          <v-card-title> Terapias con crioterapia</v-card-title>
        </v-card>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Rehab',
  props: {
    msg: String

  },
  data: () => ({
    show: false,
  }),
}
</script>
