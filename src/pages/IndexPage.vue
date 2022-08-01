<template>
  <q-page class="row items-center justify-evenly">
    <HomeLanding/>
  </q-page>
</template>

<script lang="ts">
import HomeLanding from '../components/HomeLanding.vue';
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'IndexPage',
  components: { HomeLanding },
  // setup() {
  // }
});
</script>
