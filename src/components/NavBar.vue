<template>
  <div class="navContainer">
      <q-header>
        <q-toolbar class="navBar">
        <router-link to="/">
          <img src="/img/logo.png" />
        </router-link>
          <q-toolbar-title></q-toolbar-title>
          <!-- <q-btn flat round dense icon="menu" class="q-mr-sm" /> -->
          <p class="navLink">Events</p>
          <p class="navLink">Merch</p>
          <p class="navLink">Contact</p>
        </q-toolbar>
      </q-header>
  </div>
</template>

<script lang="ts">
import { defineComponent} from 'vue';

export default defineComponent({
  name: 'NavBar',
});
</script>

<style lang="scss">

.navContainer{
  max-width:1920px;
  margin: auto;
}

.navBar{
  padding-left: 60px;
  padding-right: 60px;
  background: #FFF5F5;
  padding-top: 20px;
  padding-bottom: 20px;
}

.navLink{
  color:#403D3D;
  font-family: komet-sc,sans-serif;
  font-weight: 600;
  font-style: normal;
  font-size: 18px;
  margin-right: 45px;
}

</style>
