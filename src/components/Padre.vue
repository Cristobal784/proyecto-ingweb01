<template>
  <div>
    <Hijo mensaje="Hola desde el padre" />
    <Hijo2 mensaje="Que pasa malayas soy el hijo de en medio malditos madafakas" />
    <Hijo3 mensaje="Buena petes soy el hijo menorete" />
  </div>
</template>

<script>
import Hijo from './Hijo.vue'
import Hijo2 from './Hijo2.vue'
import Hijo3 from './Hijo3.vue'

export default {
  components: {
    Hijo,
    Hijo2,
    Hijo3
  }
}
</script>