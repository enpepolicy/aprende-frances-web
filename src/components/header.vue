<template>
  <v-app>
    <v-container id="cactus" fluid>
        <v-row id="cactustexto" align-content="center" justify="center">
          <v-col cols="10" >
            <h1>Soy Adelaïde y quiero enseñarte mi idioma <span class="rojo">frances</span> ❤</h1>
          </v-col>

          <v-col class="text-center" cols="10">
            <v-btn dark color="#4FCE5D" >Escribeme al WA</v-btn>
          </v-col>

        </v-row>
    </v-container>

  </v-app>
</template>

<script>
export default {
};
</script>

<style media="screen">
  /* azul: #0a4fff */
  #cactus{
    background-image: url('~@/assets/fondoBanner.svg');
    background-size: cover;
  }
  #cactustexto{
    height:100%;
  }
  .container{
    height: 100vh;
  }
</style>
