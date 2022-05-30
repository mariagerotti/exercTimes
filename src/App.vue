<template>
  <header>
    <span class="texto-header">Home</span>
    <span class="separador">|</span>
    <span class="texto-header">Jogadores</span>
    <span class="separador">|</span>
    <span class="texto-header">Times</span>
  </header>
  <main>main</main>
  <footer>rodapé</footer>
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  /*padding: 2rem;*/
  font-weight: normal;
  height: 100vh;
}

header,
footer {
  background-color: cornflowerblue;
  height: 15%;
  font-size: 1.3rem;
  color: white;
  display: flex;
  align-items: center;
  padding-left: 1.5rem;
}

main {
  min-height: 70%;
}

header, span{
  padding: 0 1%;
}
</style>
