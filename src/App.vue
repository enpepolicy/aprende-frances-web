<template>
  <v-app>
    <promo/>
    <headere/>
    <planes/>
    <sobre/>
  </v-app>
</template>

<script>
import promo from './components/promo'
import headere from './components/header'
import planes from './components/planes'
import sobre from './components/sobre'

export default {
  name: 'App',
  components: {
    headere,
    planes,
    sobre,
    promo
  }
};
</script>

<style media="screen">
  /* azul: #0a4fff */
  h1{
    color: black;
    text-align: center;
    font-weight: 400;
    font-size: 5vh

  }
  .rojo{
    color: #ff0032;
    font-weight:900
  }
  .v-btn__content{
    font-size: 3vh;
  }

</style>
