<template>
<div>
  <div class="hero-background">
  <div class="row heroContainer items-center justify-center">
    <div class="col-md-4">
        <h1 class="fadeIn"><span>Let's</span> <span>Make</span> <span>That</span> <span class="blue-text">Singing</span> <span>Dream.</span></h1>
        <p class="fadeInText">Where all your friends can sing, laugh, dance and rick roll each other! Free monthly events!</p>
        <div>
          <div class="row landing-button items-center fadeInButton">
            <div class="col-2">
              <q-img src="img/qr.png" class="button-icon"/>
            </div>
            <div class="col button-content">
              <p class="button-text strong">See our latest song queue</p>
              <p class="button-text little-margin-top">Start singing your own songs!</p>
            </div>
          </div>
        </div>
    </div>
    <div class="col q-pa-none">
      <q-img class="hero-image gt-sm" src="img/karaokeclubnobg.png"></q-img>
    </div>
  </div>
  </div>
  <div style="height:100vh"></div>
  </div>
</template>

<script lang="ts">
import {defineComponent} from 'vue';
export default defineComponent ({
  name: 'HomeLanding',
});
</script>

<style>
.hero-image{
  max-height: 710px;
}
.hero-background{
  width: 100vw;
  background: #FFF5F5;

}
.heroContainer{
  /* width:100%; */
  max-width: 1920px;
  height: 720px;
  margin: auto;
  padding-left:60px;
  padding-right: 20px;
  background: #FFF5F5;
  padding-bottom:120px;
}

.blue-text{
  color: #4B78A5
}

.button-icon{
  width: 42px;
}

.landing-button{
  width: 306px;
  height: 89px;
  background: #E791A0;
  border-radius: 8px;
  box-shadow: -2px 5px 6px rgb(0, 0, 0, 0.25);
}

.button-text{
  font-size: 16px;
  color:white;
  padding-left: 10px;
}

.strong{
  font-weight: bold;
  margin-bottom: 0px;
}

.landing-button{
  padding-left: 21px;
  margin-top: 18px;
}

.button-content{
  margin-top: 14px;
}

.little-margin-top{
  margin-top: -5px;
}

h1.fadeIn span{
  opacity: 0;
  transform: translateY(30px);
  animation: fadeIn 0.6s ease-out forwards;
  display:inline-block;
}

h1.fadeIn span:nth-of-type(2){
  animation-delay: 0.1s;
}

h1.fadeIn span:nth-of-type(3){
  animation-delay: 0.2s;
}

h1.fadeIn span:nth-of-type(4){
  animation-delay: 0.3s;
}

h1.fadeIn span:nth-of-type(5){
  animation-delay: 0.4s;
}

p.fadeInText{
  opacity: 0;
  transform: translateY(30px);
  animation: fadeIn 0.6s ease-out forwards;
  animation-delay: 0.4s;
}

div.fadeInButton{
  opacity: 0;
  transform: translateY(30px);
  animation: fadeIn 0.6s ease-out forwards;
  animation-delay: 0.4s;
}

.hero-image{
  opacity: 0;
  transform: translateY(30px);
  animation: fadeIn 0.4s ease-out forwards;
  animation-delay: 0.6s;
}

@keyframes fadeIn{
  to{
    opacity: 1;
    transform: translateY(0);
  }
}

</style>
