<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="Menu-superior">
    <div class="Menu-esquerdo">
      <RouterLink to="/">Home</RouterLink>
      <span>|</span>
      <RouterLink to="/Time">Time</RouterLink>
      <span>|</span>
      <RouterLink to="/Jogadores">Jogadores</RouterLink>
      <span>|</span>
    </div>
    <div class="Menu-direito">
      <span class="sair">Sair</span>
    </div>
  </header>
  <main>
    <RouterView />
  </main>
  <footer>rodape</footer>
</template>
<style>
@import "@/assets/base.css";

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
.Menu-esquerdo{
  padding: 0 10px;
  font-family: "Times New Roman", Times, serif;
}
</style>
