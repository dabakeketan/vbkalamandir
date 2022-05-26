<script setup lang="ts">
/*import { createApp } from 'vue'
import App from "./App.vue";

const app = createApp(App)

app.mount('#gallery')*/
</script>

<template>
   <div class="container common-container">
     <h3>Gallery</h3>
     <div class="row" id="gallery">
     <div class="col-sm-12 col-lg-3">
       <div class="image-wrapper">
        <img src="../assets/images/ganesh/ganesh-i.jpeg">
      </div>
     </div>
     <div class="col-sm-12 col-lg-3">
      <div class="image-wrapper">
        <img src="../assets/images/ganesh/ganesh-b.jpeg">
      </div>
     </div>
     <div class="col-sm-12 col-lg-3">
      <div class="image-wrapper">
        <img src="../assets/images/ganesh/ganesh-c.jpeg">
      </div>
     </div>
     <div class="col-sm-12 col-lg-3">
      <div class="image-wrapper">
        <img src="../assets/images/ganesh/ganesh-d.jpeg">
      </div>
     </div>
    </div>
    <div class="row" id="gallery">
     <div class="col-sm-12 col-lg-3">
      <div class="image-wrapper">
        <img src="../assets/images/ganesh/ganesh-e.jpeg">
      </div>
     </div>
     <div class="col-sm-12 col-lg-3">
      <div class="image-wrapper">
        <img src="../assets/images/ganesh/ganesh-f.jpeg">
      </div>
     </div>
     <div class="col-sm-12 col-lg-3">
      <div class="image-wrapper">
        <img src="../assets/images/ganesh/ganesh-g.jpeg">
      </div>
     </div>
     <div class="col-sm-12 col-lg-3">
      <div class="image-wrapper">
        <img src="../assets/images/ganesh/ganesh-h.jpeg">
      </div>
     </div>
    </div>
  </div>
</template>

<style>
.image-wrapper {
  height: 350px;
  overflow: hidden;
  margin-bottom: 50px;
}

.image-wrapper img {
  width: 100%;
  height: 100%;
}
@media only screen and (max-width: 768px) {
 .image-wrapper {
  height: auto;
  overflow: hidden;
} 

.image-wrapper img {
  width: auto;
  max-width: 100%;
  height: auto;
}
}
</style>
