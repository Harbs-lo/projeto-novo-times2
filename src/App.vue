<script setup>
import HeaderComp from "./components/template/HeaderComp.vue";
import RodapeComp from "./components/template/RodapeComp.vue";
</script>

<template>
  <HeaderComp />
  <RouterView />
  <RodapeComp />
</template>

<style>
@import "@/assets/base.css";

#app {
  /* max-width: 1280px; */
  /* padding: 2 rem; */
  margin: 0 auto;
  height: 100vh;

  font-weight: normal;
}

main {
  min-height: 80%;
}

/*.conteudo {
  border: 1px solid black;
  width: 100px;
  height: 50px;
  overflow: scroll;
}*/
</style>
