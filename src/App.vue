<script setup>
import HeaderCompVue from "@/components/template/HeaderComp.vue";
import RodapeCompVue from "./components/template/RodapeComp.vue";
</script>

<template>
  <HeaderCompVue />
  <main>
    <RouterView />
  </main>
  <RodapeCompVue />
</template>

<style>
@import "@/assets/base.css";
@import "@/assets/style.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  font-weight: normal;
  height: 100vh;
}
header,
footer {
  background-color: gray;
  height: 15%;
  font-size: 1.3rem;
  color: white;
  display: flex;
  align-items: center;
  padding-left: 2rem;
}
main {
  height: 70%;
}

header.Menu-superior {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
header span {
  padding: 0 10px;
}
.Menu-esquerdo {
  padding: 0 20px;
}
a {
  color: inherit;
  text-decoration: none;
}
</style>
