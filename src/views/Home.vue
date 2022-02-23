<template>
  <main class="flex-center">
    <section class="container">
      <Header />
      <Search />
      <Graph />
      <Tabs />
      <Result />
      <Chart />
    </section>
  </main>
</template>

<script>
import { surveyData } from "@/data";
import Header from "@/components/Header.vue";
import Search from "@/components/Search.vue";
import Graph from "@/components/Graph.vue";
import Tabs from "@/components/Tabs.vue";
import Result from "@/components/Result.vue";
import Chart from "@/components/Chart.vue";


export default {
  components: {
    Header, Search, Graph, Tabs, Result, Chart
  },

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
