<template>
    <div class="laser">
      <h1>Ctalogo de productos</h1>
      <div class="cards">
        <div class="laser__card card">
          <v-card class="mx-auto" max-width="344">
            <v-img src="../assets/img/productogenerico.svg" height="200px" cover></v-img>
            <v-card-title>Antimicoticos tópicos      </v-card-title>
            <v-card-title>Plantilla y almohadilla    </v-card-title>
            <v-card-title>Parches para callos          </v-card-title>
            <v-card-title>Protectores para los dedos </v-card-title>
            <v-card-title>Cremas hidratantes           </v-card-title>
            <v-card-title>Equipo de EPP              </v-card-title>
          </v-card>         
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Catalog',
    props: {
      msg: String
  
    },
    data: () => ({
      show: false,
    }),
  }
  
  
  </script>
  