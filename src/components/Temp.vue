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
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3657.1984227810517!2d-46.641267684629405!3d-23.561316067476636!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce59a5a99f7cb7%3A0x887a5a5724586542!2sAv.%20da%20Liberdade%2C%201000%20-%20Liberdade%2C%20S%C3%A3o%20Paulo%20-%20SP%2C%2001502-001!5e0!3m2!1spt-BR!2sbr!4v1629486319828!5m2!1spt-BR!2sbr" width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>

            <v-card-title primary-title>
              <div>
                <h5 class="subtitle-1 font-weight-thin">
                  Avenida Liberdade 1000, Sala 1413 - Liberdade - São Paulo
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
        <v-col class="mb-3" cols="2">
        <a alt="Whatsapp" href="https://api.whatsapp.com/send?phone=5511986281017&ltclid=">
          <v-img
            :src="require('../assets/whatsapp.png')"
            class="my-3"
            contain
            height="32"
          />
          </a>
          </v-col>
          <v-col class="mb-3" cols="2">
        <a alt="Instagram" href="https://instagram.com/dra.kataryna.olimpio">
          <v-img
            :src="require('../assets/instagram.png')"
            class="my-3"
            contain
            height="32"
          />
          </a>
          </v-col>
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
