<template>
  <div class="container">
    <app-header></app-header>
    <hr>
    <div class="row">
      <app-sunucu></app-sunucu>
      <app-serverdetail></app-serverdetail>
    </div>

    <hr>
    <app-footer></app-footer>
  </div>

</template>

<script>

import Footer from "./components/Common/Footer.vue";
import Header from "./components/Common/Header.vue";
import Sunucu from './components/Server/Sunucu.vue';
import ServerDetail from "./components/Server/SeverDetail.vue";


export default {
  components: {
    "app-header": Header,
    "app-footer": Footer,
    "app-sunucu": Sunucu,
    "app-serverdetail": ServerDetail,

  }
}


</script>

<style>
</style>
