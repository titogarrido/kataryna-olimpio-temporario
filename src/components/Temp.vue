<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/LogoCompleto.png')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col cols="12">
        <h2 class="headline font-weight-thin mb-3">
          Onde Estamos?
        </h2>

        <v-row justify="center">
          <v-card flat>
            <iframe
              width="400"
              height="300"
              id="gmap_canvas"
              src="https://maps.google.com/maps?q=R.+Borges+Lagoa,+1080+-+Vila+Clementino,+São+Paulo+-+SP,+04038-002&t=&z=17&ie=UTF8&iwloc=&output=embed"
              frameborder="0"
              scrolling="no"
              marginheight="0"
              marginwidth="0"
            ></iframe>

            <v-card-title primary-title>
              <div>
                <h5 class="subtitle-1 font-weight-thin">
                  Rua Borges Lagoa 1080, Sala 1210 - Vila Clementino - São Paulo
                </h5>
              </div>
            </v-card-title>
          </v-card>
        </v-row>
      </v-col>

      <v-col class="mb-3" cols="12">
        <h2 class="headline font-weight-thin mb-3">
          Redes Sociais
        </h2>

        <v-row justify="center">
        <a alt="Instagram" href="https://instagram.com/dra.kataryna.olimpio">
          <v-img
            :src="require('../assets/instagram.png')"
            class="my-3"
            contain
            height="32"
          />
          </a>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Temp",

  data: () => ({})
};
</script>
