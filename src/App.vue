<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import MainComponent from "./components/MainComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";

export default {
  name: "App",
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>

<template>
  <HeaderComponent class="container w-50 p-5" />

  <MainComponent />

  <FooterComponent />
</template>

<style lang="scss">
@use "assets/scss/main";
</style>
