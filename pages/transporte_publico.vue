<template>
    <div>
  <v-layout>
    <v-flex xs12 sm10 offset-sm1>
      <v-card>
        <v-img
          class="white--text"
          height="200px"
          src="/images/transportePublico.jpg"
        >
          <v-container fill-height fluid>
            <v-layout fill-height>
              <v-flex xs12 align-end flexbox>
                <h1 class="blue-grey--text text--darken-4 ">Transporte Público</h1>
              </v-flex>
            </v-layout>
          </v-container>
        </v-img>
        <v-card-title>
          <div class="pt-3">
            <h2 class="pt-3">Parts Sistemas presenta su nueva generación de soluciones inteligentes para el transporte público de pasajeros donde el límite lo define usted</h2>
            <p class="pt-4">Comenzamos nuestro camino siendo los responsables de informatizar, por primera vez, la venta de pasajes de los ferrocarriles más importantes de nuestro país. Aceptamos el desafio y diseñamos, fabricamos e instalamos más de 300 expendedoras de tickets que funcionan como una gran red interconectada de venta y recarga de tarjetas de pasajes</p>
            <p class="pt-2">Mucho tiempo ha pasado desde nuestras primeras expendedoras de pasajes y grandes cambios se han producido en las áreas de tecnología e ingeniería. A la fecha, nuestros ingenieros han desarrollado más de 15 modelos distintos de expendedoras de pasajes, molinetes de alto tránsito, carteles de información y sistemas de control de flota y seguimiento satelital</p>
          </div>
        </v-card-title>
      </v-card>
    </v-flex>
  </v-layout>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
p::first-letter {
  font-weight: bold;
  color: #FFAB00;
}
</style>
