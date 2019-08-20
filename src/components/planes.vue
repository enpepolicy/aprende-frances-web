<template lang="html">
  <v-container fluid>
      <v-row id="caja" align="center" justify="center">
        <v-col cols="12" lg="5" >
          <h1 id="titulo" >Conoce mis <span class="rojo">planes:</span></h1>


          <v-expansion-panels>

            <v-expansion-panel>
              <v-expansion-panel-header>Clases a domicilio</v-expansion-panel-header>
              <v-expansion-panel-content>
                Vivo en Escandón y puedo llegar a donde quieres, siempre y cuando no sea muy lejos. La clase es personalizada e incluye los materiales que vayamos a usar.
              </v-expansion-panel-content>
              <v-expansion-panel-content class="price">
                $200 pesos/hora
              </v-expansion-panel-content>
            </v-expansion-panel>

            <v-expansion-panel>
              <v-expansion-panel-header>Seguimiento virtual</v-expansion-panel-header>
              <v-expansion-panel-content>
                Entiendo que la movilidad puede ser un problema y con tanta tecnología, a veces innecesaria. Te propongo un monitoreo constante utilizando Skype, Whatsapp o la plataforma que quieras. Estare monitoreandote y enviando nuevos ejercicios semanales, todos ellos personalizados a tus necesidades.
              </v-expansion-panel-content>
              <v-expansion-panel-content class="price">
                $750 pesos/mensuales
              </v-expansion-panel-content>
            </v-expansion-panel>

            <v-expansion-panel>
              <v-expansion-panel-header>Preparación DELF</v-expansion-panel-header>
              <v-expansion-panel-content>
                Si estas proximo a presentar un examen de idioma, ya sea Delf o cualquier otro, realizaremos un plan de estudio intensivo que garantice buenos resultados.
              </v-expansion-panel-content>
              <v-expansion-panel-content class="price">
                A convenir
              </v-expansion-panel-content>
            </v-expansion-panel>

            <v-expansion-panel>
              <v-expansion-panel-header>Asistencia escolar</v-expansion-panel-header>
              <v-expansion-panel-content>
                Plan enfocado para niños que necesiten tutoría con las clases escolares de francés.
              </v-expansion-panel-content>
              <v-expansion-panel-content class="price">
                A convenir
              </v-expansion-panel-content>
            </v-expansion-panel>

            <v-expansion-panel>
              <v-expansion-panel-header>Servicios de traducción</v-expansion-panel-header>
              <v-expansion-panel-content>
                ¿Necesitas una traducción en tiempo express?, ¿Ingles, Frances o Español?. Yo puedo 😊
              </v-expansion-panel-content>
              <v-expansion-panel-content class="price">
                A convenir
              </v-expansion-panel-content>
            </v-expansion-panel>
          </v-expansion-panels>

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
    background-position: center bottom, right top;
    background-color: #0a4fff;
    background-size: 20vh;
    color: white;
    height: 100vh;
  }
  .price{
    text-align: right;
    color: #ff0032;
    font-weight: 900
  }
  .v-expansion-panel-content{
    font-size: 2.5vh;
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
