<template>
  <q-layout view="hHh lpR fFf">
      <NavBar/>
      <router-view />
  </q-layout>
</template>

<script lang="ts">
  import { defineComponent} from 'vue';
  import NavBar from '../components/NavBar.vue';
  export default defineComponent({
    components: {
      NavBar,
    },
  });
</script>
