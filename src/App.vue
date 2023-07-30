<script setup lang="ts">
import { onMounted } from 'vue';
    
import Rellax from 'rellax'

onMounted(() => {
  let rellax = new Rellax('.rellax');
})
</script>

<template>

    <div class="hed">
      <!-- I’m super fast!! And super centered!! -->
    </div>
    <div class="faces rellax"  data-rellax-speed="7"
      data-rellax-percentage="0.5" >
      <div class="faces-wrap loaded">
          <div ><img src="https://static.generated.photos/vue-static/home/hero/1.png" ></div>
          <div ><img src="https://static.generated.photos/vue-static/home/hero/2.png" data-rellax-speed="-1" class="rellax"  style="transform: translate3d(0px, 11px, 0px);"></div>
          <div ><img src="https://static.generated.photos/vue-static/home/hero/3.png" data-rellax-speed="-2" class="rellax"  style="transform: translate3d(0px, 21px, 0px);"></div>
          <div ><img src="https://static.generated.photos/vue-static/home/hero/4.png" data-rellax-speed="2" class="rellax"  style="transform: translate3d(0px, -21px, 0px);"></div>
          <div ><img src="https://static.generated.photos/vue-static/home/hero/5.png" data-rellax-speed="-2" class="rellax"  style="transform: translate3d(0px, 21px, 0px);"></div>
          <div ><img src="https://static.generated.photos/vue-static/home/hero/6.png" data-rellax-speed="2" class="rellax"  style="transform: translate3d(0px, -21px, 0px);"></div>
          <div ><img src="https://static.generated.photos/vue-static/home/hero/7.png" class="rellax"  style="transform: translate3d(0px, 21px, 0px);"></div>
          <div ><img src="https://static.generated.photos/vue-static/home/hero/8.png" ></div>
      </div>
    </div>
</template>

<style scoped>
/* .hed{
  display: flex;
  height: 1000px;
} */
.faces{
  margin-top:400px;
   box-sizing: border-box;
    color: rgb(255, 255, 255);
    display: block;
    font-family: Inter, "Helvetica Neue", "Segoe UI", "Fira Sans", Roboto, Oxygen, Ubuntu, "Droid Sans", Arial, sans-serif;
    font-size: 14px;
    font-weight: 400;
    height: 400px;
    line-height: 22px;
    margin-bottom: 1980px;
    max-height: 400px;
    position: relative;
    text-rendering: optimizelegibility;
    text-size-adjust: 100%;
    width: 1890px;
    -webkit-font-smoothing: antialiased;
}

.faces .faces-wrap.loaded {
    opacity: 1;
    visibility: visible;
}

.faces .faces-wrap.loaded {
    opacity: 1;
    visibility: visible;
}

.faces .faces-wrap {
    bottom: 0;
    display: flex;
    justify-content: space-between;
    left: 0;
    opacity: 0;
    position: absolute;
    right: 0;
    top: 0;
    transition: all .5s linear;
    visibility: hidden;
}
.faces .faces-wrap div:first-child img {
    margin-top: 130%;
    z-index: 1;
}

.faces .faces-wrap div:first-child img {
    margin-top: 130%;
    z-index: 1;
}

.faces .faces-wrap div img {
    display: block;
    max-height: 200px;
    max-width: 100%;
    position: relative;
    z-index: 0;
}
.faces .faces-wrap div img {
    display: block;
    max-height: 200px;
    max-width: 100%;
    position: relative;
    z-index: 0;
}
</style>
