<script></script>
<template>
  <main id="main">
    <div class="cadastro">
      <h1 style="font-size: 3rem; color: black">Livraria Website</h1>
      <hr class="cadastro-title-hr" />
      <!-- <h1 style="font-size: 2rem; color: black; margin-bottom: 5px">Visualizar</h1> -->
      <div class="cadastro-options">
        <!-- <span class="cadastro-option">Editoras</span> -->
        <!-- <span class="cadastro-option">Categorias</span> -->
        <!-- <span class="cadastro-option">Autores</span> -->
        <RouterLink to="livros" class="cadastro-option">Navegar</RouterLink>
      </div>
    </div>
  </main>
</template>
<style scoped>
#main {
  padding: 3vh;

  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: stretch;

  color: whitesmoke;
  background-color: rgb(200, 20, 50);
}
.cadastro {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.cadastro-title-hr {
  margin: 10px 0px 20px 0px;
  width: 50rem;
}
.cadastro-options {
  display: flex;
  flex-direction: row;

  font-size: 2rem;
  color: rgb(0, 182, 237);
  font-weight: bolder;
}
.cadastro-option {
  padding: 1vh;
}
.cadastro-option:hover {
  background-color: gray;
  cursor: pointer;
}
</style>
