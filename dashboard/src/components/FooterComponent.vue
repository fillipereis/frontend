<!-- Footer Bombordo -->
<template>
  <div>
    <v-app style="background: #20b2aa">
      <v-footer app width="auto" color="#20b2aa">
        <v-card-text>
          <c-card-text class="white--text pt-0"> Siga-nos </c-card-text>
          <v-btn
            v-for="icon in icons"
            :key="icon"
            class="mx-4 white--text"
            icon
          >
            <v-icon size="24px">{{ icon }}</v-icon>
          </v-btn>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-text class="white--text">
         &copy; {{ new Date().getFullYear() }}-{{ new Date().getFullYear() }}
          <strong
            >Bombordo. Todos os direitos reservados. Rua pampulha, centro - Rio
            de Janeiro RJ. Termos e condições Política de privacidade
          </strong>
        </v-card-text>
      </v-footer>
    </v-app>
  </div>
</template>

<script>
export default {
  name: "FooterComponent",

  data: () => ({
    icons: ["mdi-facebook", "mdi-instagram", "mdi-twitter", "mdi-youtube"],
  }),
};
</script>

<style scoped></style>
