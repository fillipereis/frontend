<!-- Dashboard Bombordo -->
<template>
  <nav>
    <v-app>
      <v-app-bar color="#20b2aa">
        <div>
          <v-img
            alt="Vuetify Logo"
            class="shrink mr-2"
            contain
            src="./assets/logo.svg"
            transition="scale-transition"
            width="40"
          />
        </div>
        <toolbar-title style="color: white; font-weight: bold">
          BOMBORDO
        </toolbar-title>

        <v-spacer></v-spacer>
        <v-btn href="#" color="white" text>
          <span class="mr-1">Home</span>
        </v-btn>

        <v-btn href="#" color="white" text>
          <span class="mr-1">Destinos</span>
        </v-btn>

        <v-btn href="#" color="white" text>
          <span class="mr-1">Serviços</span>
        </v-btn>

        <v-btn href="#" color="white" text>
          <span class="mr-1">Dúvidas frequentes</span>
        </v-btn>

        <v-btn class="btnRegister" href="#" color="white" outlined>
          Registre seu barco
        </v-btn>

        <v-btn class="lightgreen--text" href="#" color="white"> Login</v-btn>
      </v-app-bar>

      <v-main>
        <router-view />
      </v-main>
    </v-app>
  </nav>
</template>

<script>
export default {
  name: "App",

  data: () => ({}),
};
</script>

<style scoped>
.btnRegister {
  margin: 0 1.3rem 0 0;
}
</style>
