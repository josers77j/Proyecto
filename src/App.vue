<template>
  <div id="app">
    <BarraNavegacion msg="Prueba1"/>
  </div>
</template>
<!--Aquí se exportan los componentes para mostrar en index-->
<script>
import BarraNavegacion from './components/BarraNavegacion.vue'

export default {
  name: 'App',
  components: {
    BarraNavegacion
  }
}
</script>

