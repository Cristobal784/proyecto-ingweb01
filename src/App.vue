<template>
  <div id="app" style="padding: 20px;">
    
    <h2>Actividad 1: Componente inicial</h2>
    <HelloWorld msg="¡Hola desde la Actividad 1!" />
    <hr style="margin: 40px 0;">

    <h2>Actividades 2 y 3: Componentes y Eventos</h2>
    <Padre />
    <hr style="margin: 40px 0;">

    <h2>Actividad 4: Formulario y v-model</h2>
    <Contacto />
    <hr style="margin: 40px 0;">

    <h2>Actividad 5: Lista de Tareas</h2>
    <Tareas />
    
  </div>
</template>

<script>

import HelloWorld from './components/HelloWorld.vue'
import Padre from './components/Padre.vue'
import Contacto from './components/Contacto.vue'
import Tareas from './components/Tareas.vue' // <-- Nuevo import

export default {
  components: {
    HelloWorld,
    Padre,
    Contacto,
    Tareas
  }
}
</script>