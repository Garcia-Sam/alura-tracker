<script lang="ts">
import { defineComponent } from 'vue';
import Formulario from './components/Formulario.vue';
import BarraLateral from './components/BarraLateral.vue';

export default defineComponent({
  name: 'App',
  components: {
    BarraLateral, Formulario
  }
});
</script>

<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral />
    </div>

    <div class="column is-three-quarter">
      <Formulario />
    </div>
  </main>
</template>

<style></style>
