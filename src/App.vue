<template>
  <v-app>
    <headere/>
    <planes/>
  </v-app>
</template>

<script>
import headere from './components/header'
import planes from './components/planes'

export default {
  name: 'App',
  components: {
    headere,
    planes
  },
  data: () => ({
    //
  }),
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
