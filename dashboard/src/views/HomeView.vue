<template>
  <div>
    <home-component />
    <footer-component />
    
  </div>
</template>

<script>
import HomeComponent from "../components/HomeComponent";
import FooterComponent from "../components/FooterComponent";

export default {
  name: "HomeView",

  components: {
    HomeComponent,
    FooterComponent
  },
};
</script>
