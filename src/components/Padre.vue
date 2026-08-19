<template>
  <div>
    <div style="margin-bottom: 20px;">
      <Hijo mensaje="Hola desde el padre" />
      <Hijo2 mensaje="Que pasa malayas soy el hijo de en medio malditos madafakas" />
      <Hijo3 mensaje="Buena petes soy el hijo menorete" />
    </div>

    <div style="background-color: #f0f0f0; padding: 10px; border-radius: 5px;">
      <p><strong>Prueba de evento:</strong></p>
      <HijoBoton @saludo="mostrarSaludo" />
      <p v-if="mensaje" style="color: green; font-weight: bold;">{{ mensaje }}</p>
    </div>
  </div>
</template>

<script>

import Hijo from './Hijo.vue'
import Hijo2 from './Hijo2.vue'
import Hijo3 from './Hijo3.vue'
import HijoBoton from './HijoBoton.vue'

export default {
  components: {
    Hijo,
    Hijo2,
    Hijo3,
    HijoBoton
  },
  data() {
    return { 
      mensaje: '' 
    }
  },
  methods: {
    mostrarSaludo() {
      this.mensaje = 'Hola desde el hijo';
    }
  }
}
</script>