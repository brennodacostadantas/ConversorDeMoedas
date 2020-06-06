<template>
  <div id="app">
    <h1> Conversor de Moedas </h1>
    <div class="linha">
    <Conversor moeda-a="USD" moeda-b="BRL"/>
    <Conversor moeda-a="BRL" moeda-b="USD"/>
    </div>
    <div class="linha">
    <Conversor moeda-a="EUR" moeda-b="BRL"/>
    <Conversor moeda-a="BRL" moeda-b="EUR"/>
    </div>
    <div class="linha">
    <Conversor moeda-a="JPY" moeda-b="BRL"/>
    <Conversor moeda-a="BRL" moeda-b="JPY"/>
    </div>
    <div class="linha">
    <Conversor moeda-a="USD" moeda-b="JPY"/>
    <Conversor moeda-a="JPY" moeda-b="USD"/>
    </div>
    <div class="linha">
    <Conversor moeda-a="USD" moeda-b="EUR"/>
    <Conversor moeda-a="EUR" moeda-b="USD"/>
    </div>
    <div class="linha">
    <Conversor moeda-a="USD" moeda-b="GBP"/>
    <Conversor moeda-a="GBP" moeda-b="USD"/>
    </div>
    <div class="linha">
    <Conversor moeda-a="BRL" moeda-b="GBP"/>
    <Conversor moeda-a="GBP" moeda-b="BRL"/>
    </div>
  </div>
</template>

<script>
import Conversor from './components/Conversor.vue'

export default {
  name: 'App',
  components: {
    Conversor
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.linha{
  display: flex;
  justify-content: space-around;
}
</style>
