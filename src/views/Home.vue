<template>
  <main class="flex-center">
    <section class="container" />
  </main>
</template>

<script>
import { surveyData } from "@/data";

export default {
  components: {},

  data() {
    return {
      surveyData,
      comparisonCompany: null,
    };
  },

  methods: {
    showAlert() {
      alert(this.name);
    },

    componenets: {},
  },
};
</script>

<style>
main {
  width: 100vw;
  height: 100vh;
  background-color: #e5e5e5;
}

.container {
  width: 360px;
  height: 785px;
  background-color: #fff;
}
</style>
