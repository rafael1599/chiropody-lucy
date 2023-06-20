<template>
  <div class="laser">
    <h1>TRATAMIENTOS CON LASER</h1>
    <div class="cards">
      <div class="laser__card card">
        <v-card class="mx-auto" max-width="344">
          <v-img src="../assets/img/laser1.svg" height="200px" cover></v-img>
          <v-card-title> Tratamiento con láser</v-card-title>
          <v-card-title> Onicomicosis</v-card-title>
        </v-card>
      </div>
      <div class="laser__card card">
        <v-card class="mx-auto" max-width="344">
          <v-img src="../assets/img/laser2.svg" height="200px" cover></v-img>
          <v-card-title> Tratamiento con láser</v-card-title>
          <v-card-title> Onicomicosis</v-card-title>
        </v-card>
      </div>
      <div class="laser__card card">
        <v-card class="mx-auto" max-width="344">
          <v-img src="../assets/img/laser3.svg" height="200px" cover></v-img>
          <v-card-title> Tratamiento con láser</v-card-title>
          <v-card-title> Onicomicosis</v-card-title>
        </v-card>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Laser',
  props: {
    msg: String

  },
  data: () => ({
    show: false,
  }),
}


</script>
