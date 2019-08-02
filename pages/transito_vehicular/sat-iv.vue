<template>
  <div>
    <v-layout>
      <v-flex
        xs12
        sm10
        offset-sm1
      >
        <v-card>
          <v-img
            class="white--text"
            height="250px"
            src="/images/transporteVehicular.jpg"
          >
            <v-container
              grid-list-md
              fluid
            >
              <v-layout 
                row
                wrap
              >
                <h1 class="blue-grey--text text--darken-4">Tránsito Vehicular</h1>
              </v-layout>
            </v-container>
            <v-card-actions class="mt-5 pt-5">
              <v-spacer></v-spacer>
              <menuTransitoVehicular />
            </v-card-actions>
          </v-img>
          <v-card-title>
            <div class="pt-3">
              <h2 class="pt-3 pl-4">SAT-IV</h2>
              <h4 class="pt-3 pl-4 pr-4">El Apolo II es un sistema inteligente microcontrolado que ayuda a la prevención de accidentes detectando e informando la aproximación y velocidad de los vehículos</h4>
              <v-container
                fluid
                grid-list-md
              >
                <v-layout
                  row
                  wrap
                >
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text class="px-0">
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">Las estadísticas muestran que en accidentes de tránsito a menos de 35 km/h solo una de cada diez personas muere, mientras que en accidentes de tránsito a más de 60 km/h solo una de cada diez personas sobrevive. Estas cifras muestran lo importante que es contar con medios de prevención e información que ayuden a reducir y evitar estos accidentes.</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text class="px-0">
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">El Apolo II fué pensado para dar respuesta a esta necesidad. Previene la posibilidad de una colisión informando a los vehículos que se acercan a una intersección si por las otras calles se aproximan otros vehículos. También, alerta al conductor cuando está excediendo la velocidad máxima. Además, transmite información para aplicar mejoras a las medidas de preven ción.</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-btn color="warning" fab dark>
                      <v-icon>account_circle</v-icon> 
                    </v-btn>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark>
                    <v-icon>cancel</v-icon>
                  </v-btn>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark>
                    <v-icon>account_group</v-icon>
                  </v-btn>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark>
                    <v-icon>account_circle</v-icon>
                  </v-btn>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark>
                    <v-icon>account_circle</v-icon>
                  </v-btn>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark>
                    <v-icon>account_circle</v-icon>
                  </v-btn>
                  </v-flex>
                </v-layout>
              </v-container>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
    </v-layout>
  </div>
</template>

<script>
import menuTransitoVehicular from '~/components/menuTransitoVehicular';
export default {
  components: {
    menuTransitoVehicular
  },
  head:{
    title: 'Tránsito Vehicular'
  },
};
</script>

<style scoped>
p::first-letter {
  font-weight: bold;
  color: #ffab00;
  font-size: 18px;
}
</style>
