<script></script>

<template>
  <main>
    <div class="calculadora">
      <label>Insira o valor "A"</label>
      <br />
      <input type="number" id="valorA" />
      <br />
      <label>Insira o valor "B"</label>
      <br />
      <input type="number" id="valorB" />
      <br />
      <label>Insira o valor "C"</label>
      <br />
      <input type="number" id="valorC" />
    </div>
    <div class="botao">
      <button id="BtnCalcular">Calcular</button>
    </div>
    <div class="resultado">
      <label id="resulx1">Resultado X1:</label>
      <input type="text" id="resultadoX1" />
      <br /><br />
      <label id="resulx2">Resultado X2:</label>
      <input type="text" id="resultadoX2" />
    </div>
  </main>
</template>

<style>
body {
  background-color: rgb(199, 218, 250);
  margin: 10%;
}

.calculadora {
  padding-top: 2%;
  padding-bottom: 5%;
  justify-content: center;
  background-color: rgb(74, 150, 150);
  padding-left: 35%;
}

.resultado {
  justify-content: center;
  background-color: rgb(74, 150, 150);
  padding-top: 5%;
  padding-bottom: 2%;
  padding-left: 28%;
}

.botao {
  justify-content: center;
  background-color: rgb(74, 150, 150);
  padding-left: 45%;
  padding-top: 2%;
}
main {
  width: 40%;
  padding-left: 30%;
}
</style>
