<template>
    <div class="contacto">
        <div class="footer-logos">
            <div class="footer-social">
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
        <div class="footer-text">
            <p style="font-weight: 600;">Horario</p>
            <p>Lunes a viernes de 9:00 am - 7:00 pm</p>
            <p>Sábado de 9:00 am - 2:00 pm</p>
            <p style="margin-bottom: 50px;"></p>

            <p style="font-weight: 600;">Telefono</p>
            <p>933-109-845</p>
            <p style="margin-bottom: 50px;"></p>

            <p style="font-weight: 600;">whatsapp</p>
            <p>933-109-845</p>
            <p style="margin-bottom: 50px;"></p>

            <p style="font-weight: 600;">Email</p>
            <p>lucindalazarocruz@gmail.com</p>
            <p style="margin-bottom: 50px;"></p>
        </div>

    </div>
    <v-footer color="#498B86" padless>

        <v-row justify="center" no-gutters>
            <v-btn v-for="link in links" :key="link" color="white" text rounded class="ml-2">
                {{ link }}
            </v-btn>
            <v-col class="primary lighten-2 py-4 text-center white--text text" cols="12">
                {{ new Date().getFullYear() }} — <strong>Confi </strong>
            </v-col>
        </v-row>
    </v-footer>
</template>

<script>
export default {
    name: "Footer",
    data: () => ({
        links: [
            'Home',
            'Acerca de nosotros',
            'Nuestro equipo',
            'Nuestros servicios',
            'Terapias especializadas',
            'Contactanos',
        ]
    }),

};
</script>

<style>
.contacto{
    background-color: rgb(73, 139, 134);
}
</style>