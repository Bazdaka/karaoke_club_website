<template>
  <q-layout view="hHh lpR fFf">

    <q-page-container>
      <NavBar/>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<script lang="ts">
  import { defineComponent, ref } from 'vue';
  import NavBar from '../components/NavBar.vue';
  export default defineComponent({
    components: {
      NavBar,
    },
  });
</script>
