<template lang="html">
  <v-container fluid>
      <v-row id="caja" align-content="center" justify="center">
        <v-col cols="10" lg="5" >
          <h1 id="titulo" ><span class="rojo">Sobre mi...</span></h1>
          <p>Soy francesa y tengo 23 años. Me encuentro en CDMX estudiando una maestria en comercio de arte y gestion cultural. Vengo de una familia de profes y siempre me ha gustado enseñar.</p><br>
          <h2>📩 <em>adelaide.keraldy@gmail.com</em></h2>

        </v-col>

        <v-col cols="12" >
          <v-img
          max-height="5em"
          contain
          :src="require('../assets/peyote.png')"
          />
        </v-col>

        <v-col class="text-center" cols="12">
          <v-btn large dark color="#ff0032" href="https://api.whatsapp.com/send?text=✋Hola%20Ade,%20me%20puedes%20dar%20mas%20información%20sobre%20los%20planes?&phone=525539537088" >Escribeme directo</v-btn>
        </v-col>

      </v-row>


  </v-container>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
  /* azul: #0a4fff */
  h1{
    color: white;
    font-weight: 700;
  }
  p{
    color: black;
    font-size: 3vh;
    font-weight: 700;
  }
  li{
    text-align: center;
  }
  h2{
    text-align: center;
  }
  .container{
    background-image: url('~@/assets/cactusazulinv.svg'), url('~@/assets/torre.svg');
    background-position: right top, left bottom;
    background-size: 10vh, 80vw;
    background-color: #fff;
    height: 100vh;
  }
  .v-expansion-panel-header{
    color: #0a4fff;
    font-size: 3.5vh
  }
  #caja{
    height: 100%
  }
  #titulo{
    color: #ffffff;
    margin-bottom: 1em;
    /* background-color: white */

  }

</style>
