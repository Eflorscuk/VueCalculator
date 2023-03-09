<template>
  <div id="app">
    <h1>Calculadora</h1>
    <p>Em resumo, o App.vue é um componente fundamental em projetos Vue.js criados com o Vue CLI, 
      pois ele é o componente principal da sua aplicação e é responsável por definir a estrutura HTML, 
      a lógica JavaScript e o estilo CSS do seu aplicativo.</p>
  </div>
</template>

<script>
export default {

}
</script>

<style>
@font-face {
  font-family: "RobotoMono";
  src: url("./fonts/RobotoMono-Thin.ttf");
}

* {
  font-family: "RobotoMono", monospace;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;

  color: #fff;
  background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}
</style>