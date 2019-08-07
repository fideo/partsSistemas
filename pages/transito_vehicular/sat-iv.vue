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
            src="/images/sat-iv.jpg"
          >
            <v-container
              grid-list-md
              fluid
            >
              <v-layout 
                row
                wrap
              >
                <h1 class="blue-grey--text text--darken-4 sombraBlanca">Tránsito Vehicular</h1>
              </v-layout>
            </v-container>
            <v-card-actions class="mt-5 pt-5">
              <v-spacer></v-spacer>
              <menuTransitoVehicular />
            </v-card-actions>
          </v-img>
          <v-card-title>
            <v-flex
              d-flex
              xs12
              sm12
              md12>
              <div class="display-1 text-md-center text-xs-center text-sm-center pt-4 pb-4 amber white--text">Sistema de Advertencia Temprana para Intersecciones Vehiculares Modelo Apolo II</div>
            </v-flex>
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
                    d-flex
                    xs12
                    sm4
                    md4
                  >
                    <v-img
                      class="white--text"
                      height="300px"
                      src="/images/sat-iv_2.jpg"
                    ></v-img>
                  </v-flex>
                  <v-flex
                    xs12
                    sm8
                    md8
                    pl-3
                    text-md-justify text-xs-justify
                  >
                    <div class="title pb-2">Apolo II</div>
                    <p>El Apolo II es un Sistema de Advertencia Temprana (SAT) formado por radares dopplers que permiten la detección y medición de velocidad de los vehículos que se aproximan hacia él. Los vehículos detectados son informados a los demás vehículos que se acercan a una intersección mediante las pantallas ubicadas en cada una de las caras. Estás pantallas presentan unas señales que indican el sentido en el que se desplaza un vehículo. Las señales se activan en forma sucesiva e incrementan su ritmo de activación a medida que el vehículo se acerca más a la intersección.</p>
                    <p>Cuando un vehículo supera la velocidad máxima permitida, el Apolo II detecta esta situación gracias a sus radares e inmediatamente muestra, en la pantalla correspondiente a ese vehículo, un mensaje con la leyenda PARE. Este mensaje se mostrará de forma intermitente en la pantalla hasta que el vehículo disminuya la velocidad por debajo de la máxima permitida.</p>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-btn color="warning" fab dark small>
                      <v-icon>map</v-icon>
                    </v-btn>
                    <span class="caption "> Protección de intersecciones y cruces de calles peligrosas</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>cancel</v-icon>
                  </v-btn>
                    <span class="caption "> Advertencia visual de exceso de velocidad y proximidad</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>wifi</v-icon>
                  </v-btn>
                    <span class="caption "> Medición de velocidad de 15 km/h hasta 150 km/h</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>account_circle</v-icon>
                  </v-btn>
                    <span class="caption "> Conteo y registro de vehículos circurlantes</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>my_location</v-icon>
                  </v-btn>
                    <span class="caption "> Rango de sensado de hasta 100 metros de distancia</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>device_hub</v-icon>
                  </v-btn>
                    <span class="caption "> Monitoreo y administración remota y centralizada</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>cloud_upload</v-icon>
                  </v-btn>
                    <span class="caption "> Transmisión de información a base central de monitoreo</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>brightness_5</v-icon>
                  </v-btn>
                    <span class="caption "> Alimentación sustentada con paneles solares</span>
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
    title: 'SAT-IV - Tránsito Vehicular '
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
