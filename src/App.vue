<template>
  <RouterView />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: calc(100-1.5rem);
  margin: 0 auto;
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
  justify-content: space-between;
}

main {
  min-height: 70%;
}

header span {
  padding: 0 10px;
}
</style>
