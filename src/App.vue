<template>
  <div id="app">
    <header>
      <span>Vue.js PWA</span>
    </header>
    <main>
      <img src="./assets/logo.png" alt="Vue.js PWA">
      <hello></hello>
    </main>
  </div>
</template>

<script>
import Panel from "./components/Panel.vue";
import InputForm from "./components/InputForm";
import Result from "./components/Result";
import { calcTaxes } from "./calc.js";

export default {
  name: 'app',
  components: {
    Panel,
    InputForm,
    Result
  }
}
</script>

<style lang="scss" src="./assets/styles/App.scss"/>