<template>
  <h1>Vuejs</h1>
  <calculator-main />
</template>

<script>

import CalculatorMain from "./main/CalculatorMain.vue"

export default {
  name: 'App',
  components: {
    CalculatorMain
  }
}
</script>

<style>

@font-face {
  font-family: "RobotoMono";
  src: url("./assets/fonts/RobotoMono-Thin.ttf");
}

* {
  font-family: "RobotoMono", monospace;
}

body {
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;

  color: #fff;
  background: linear-gradient(to right, rgb(83,105,118), rgb(41,46,73));
}

</style>
