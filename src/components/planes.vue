<template lang="html">
  <v-container fluid>
      <v-row id="caja" align-content="center" justify="center">
        <v-col cols="12" lg="4" >
          <h1 id="titulo" >Conoce mis planes:</h1>


          <v-expansion-panels>

            <v-expansion-panel>
              <v-expansion-panel-header>Clases a domicilio</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>

            <v-expansion-panel>
              <v-expansion-panel-header>Seguimiento virtual</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>

            <v-expansion-panel>
              <v-expansion-panel-header>Preparacion DELF</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>

            <v-expansion-panel>
              <v-expansion-panel-header>Asistencia escolar</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>

            <v-expansion-panel>
              <v-expansion-panel-header>Servicios de traduccion</v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>


          </v-expansion-panels>

          <!-- <v-card>
            <v-card-title>Clases a domicilio</v-card-title>
          </v-card>
          <v-card color="transparent">
            <v-card-title>Seguimiento virtual</v-card-title>
          </v-card>
          <v-card>
            <v-card-title>Preparacion DELF</v-card-title>
          </v-card> -->


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
  li{
    text-align: center;
  }
  .container{
    background-image: url('~@/assets/cactusblanco.svg'), url('~@/assets/cactusblancoinv.svg');
    background-position: center bottom, center top;
    background-color: #0a4fff;
    background-size: 20vh;
    color: white;
    height: 100vh;
  }
  #caja{
    height: 100%
  }
  #titulo{
  }


</style>
