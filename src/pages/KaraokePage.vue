<template>
  <q-page style="background-color:#FFF5F5">
    <div class="karaoke_container justify-center">
      <h1>Queue your song</h1>
      <p class="description-text">Find the song of choice on YouTube and it will be automatically added to the list!</p>
      <div class="window-width outer-container">
      <div class="row landing-button justify-center items-center">
        <div class="col-1">
          <q-img src="img/youtube.png" class="button-icon"/>
        </div>
        <div class="col button-content">
          <p class="button-text">Never gonna give you up....</p>
        </div>
        </div>
    </div>
    </div>
  </q-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
   name: 'KaraokePage'
})
</script>

<style scoped>

.outer-container{
  display: flex;
  justify-content: center;
  align-items: center;
}
.karaoke_container{
  padding-top: 150px;
  text-align: center;
  align-items: center;
  justify-items: center;
}

.description-text{
  padding-top:5px;
}
.button-icon{
  width: 42px;
}

.landing-button{
  width: 350px;
  height: 89px;
  background: #E791A0;
  border-radius: 8px;
  box-shadow: -2px 5px 6px rgb(0, 0, 0, 0.25);
  padding-left: 30px;
  padding-right:30px;
  margin-top: 18px;
}

.button-text{
  font-size: 16px;
  color:white;
  padding-left: 10px;
  font-weight: 500;
}
</style>
