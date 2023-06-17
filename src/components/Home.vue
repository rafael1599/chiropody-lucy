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
        <p>¡Cuida tus pies, regala bienestar! Con nuestros servicios podológicos especializados y terapias rehabilitadoras, caminarás hacia una vida más saludable.</p>
      </div>
    </div>
    <div class="landing__img">
      <img src="../assets/podiatry-landing.jpg">
    </div>
  </div>
  <div class="services">
    
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.social img{
  margin-left: 10px;
}
.logos{
  display: flex;
  justify-content: space-around;
}
.home{
  display: flex;
  padding: 0 50px 0 50px;
}

.desc{
  padding-right: 50px;
}
.landing__img{
  padding: 0 30px 0;
}

.text h1{
  @import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&family=Roboto:wght@300&display=swap');
  font-family: 'Roboto', sans-serif;
  font-size: 40px;

}
.text p{
  font-family: 'Josefin Sans', sans-serif;
  font-size: 32px;
}
</style>
