<template>
  <div id="App">
    <TainaraHeader />
    <TainaraSection />
    <TainaraFooter />
  </div>
</template>

<script>
import TainaraHeader from "./components/TainaraHeader";
import TainaraSection from "./components/TainaraSection";
import TainaraFooter from "./components/TainaraFooter";

export default {
  name: "App",
  components: {
    TainaraHeader,
    TainaraSection,
    TainaraFooter,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Rajdhani&display=swap");
</style>
