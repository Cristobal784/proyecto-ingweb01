<template>
  <div id="app" style="padding: 20px;">
    
    <h2>Actividades 2 y 3: Componentes y Eventos</h2>
    <Padre />

    <hr style="margin: 40px 0;">

    <h2>Actividad 4: Formulario y v-model</h2>
    <Contacto />
    
  </div>
</template>

<script>
import Padre from './components/Padre.vue'
import Contacto from './components/Contacto.vue'

export default {
  components: {
    Padre,
    Contacto
  }
}
</script>