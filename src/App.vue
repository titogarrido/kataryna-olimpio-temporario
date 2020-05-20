<template>
  <v-app>
    <v-app-bar
      app
      color="white"
      light
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          :src="require('@/assets/logo.png')"
          transition="scale-transition"
          width="40"
        />

        <!-- <h1 class="shrink mt-1 hidden-sm-and-down black--text"></h1> -->
      </div>

      <v-spacer></v-spacer>

      <v-btn light
        href="https://linktr.ee/agendaraqui"
        target="_blank"
        text
      >
        <span class="mr-2">Agende uma Consulta</span>
        <v-icon>mdi-calendar</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <Temp/>
    </v-content>
  </v-app>
</template>

<script>
import Temp from './components/Temp';

export default {
  name: 'App',

  components: {
    Temp,
  },

  data: () => ({
    //
  }),
};
</script>
