<template>
    <v-container id="cactus" fluid>
        <v-row id="cactustexto" align-content="center" justify="center">
          <v-col cols="10" >
            <h1>Soy Adélaïde y quiero enseñarte <span class="rojo">francés</span> ❤</h1>
          </v-col>

          <v-col class="text-center" cols="10">
            <v-btn href="https://api.whatsapp.com/send?text=✋Hola%20Ade,%20me%20puedes%20dar%20mas%20información%20sobre%20los%20planes?&phone=573164961184" dark color="#4FCE5D" >Escribeme al WA</v-btn>
          </v-col>

        </v-row>
    </v-container>

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
