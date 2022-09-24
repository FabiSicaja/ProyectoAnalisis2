<template>
  <Pantalla_Inicio/>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import Pantalla_Inicio from '@/components/Pantalla_Inicio.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    Pantalla_Inicio
},
});
</script>
