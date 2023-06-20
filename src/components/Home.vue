<template>
  <div class="home">
    <div class="desc">
      <div class="logos">
        <div class="img__logo">
          <v-img src="../assets/img/logo.svg"></v-img>
        </div>
        <div class="social">
          <a href="http://www.facebook.com" target="_blank" class="logo"><v-img src="../assets/img/f.svg"
              alt="facebook"></v-img> </a>
          <a href="http://www.whatsapp.com" target="_blank" class="logo"><v-img src="../assets/img/w.svg"
              alt="whatsapp"></v-img> </a>
          <a href="http://www.instagram.com" target="_blank" class="logo"><v-img src="../assets/img/i.svg"
              alt="ig"></v-img>
          </a>
          <a href="http://mail.google.com" target="_blank" class="logo"><v-img src="../assets/img/m.svg"
              alt="email"></v-img>
          </a>
        </div>
      </div>
      <div class="text">
        <h1>SERVICIO PODOLÓGICO ESPECIALIZADOS Y TERAPIAS REHABILITADORAS</h1>
        <p>¡Cuida tus pies, regala bienestar! Con nuestros servicios podológicos especializados y terapias
          rehabilitadoras, caminarás hacia una vida más saludable.</p>
      </div>
    </div>
    <div class="landing__img">
      <v-img src="../assets/img/podiatry-landing.jpg" alt="landing image"></v-img>
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

