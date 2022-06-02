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
      <span class="sair"><RouterLink to="/">Sair</RouterLink></span>
    </div>
  </header>
  <!-- <main></main> -->
  <!-- <footer>rodape</footer> -->
</template>
<style>
header span {
  padding: 0 20px;
}

.menusuperior {
  justify-content: space-between;
}
</style>
