<template>
  <div id="app">
    <h1>Calculator</h1>
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./main/Calculator"

export default {
  components: {
    Calculator
  }
}
</script>

<style>
* {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
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

  color: rgb(255, 255, 255);
  background: #ccff00;
}
</style>
