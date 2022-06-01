<template>
<header class="menu-superior">
    <div class="menu-esquerdo">
      <span>Home</span>
      <span>|</span>
      <span>Times</span>
      <span>|</span>
      <span>Jogadores</span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
  <RouterView />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  /*padding: 2rem;*/
  height: 100vh;

  font-weight: normal;
}
header {
  background-color: rgb(207, 207, 207);
  color: rgb(0, 0, 0);
  height: 5%;
  font-size: 1.3rem;
}
footer {
  background-color: rgb(133, 133, 138);
  color: rgb(0, 0, 0);
  height: 15%;
  font-size: 1.3rem;
}

header.menu-superior {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

main {
  height: 80%;
  background-color: rgb(255, 255, 255);
  color: crimson;
}

header span {
  padding: 0 20px;
}
</style>
