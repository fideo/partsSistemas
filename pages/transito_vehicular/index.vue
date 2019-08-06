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
              <h2 class="pt-3 pl-4">Parts Sistemas cuenta con una amplia gama de productos para el control de tránsito y sistemas para prevenir y evitar accidentes en la vía pública</h2>
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
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">Comenzamos desarrollando sistemas de estacionamiento medido mediante parquímetros y luego incorporamos sistemas de registración de estacionamiento mediante telefonía celular. Posteriormente incursionamos en el mercado semafórico desarrollando contadores de cuenta regresiva inteligentes que se adaptan automaticamente a la red semafórica existente y no necesitan preprogramación</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text class="px-0">
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">Actualmente111 estamos ofreciendo sistemas de control de tránsito de última generación basados en radares que permiten detectar excesos de velocidad, invasión de senda peatonal y cruce de semáforos con luz roja. Así mismo, estamos presentando el nuevo Sistema de Advertencia Temprana de Intersecciones Vehiculares basado también en tecnología no intrusiva</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4
                  >
                  <v-img
                    class="white--text"
                    height="250px"
                    src="/images/controlesDeEstacionamiento.jpg"
                  />
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4
                  >
                  <v-img
                    class="white--text"
                    height="250px"
                    src="/images/controlesDeSemaforos.jpg"
                  />
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4
                  ><v-img
                    class="white--text"
                    height="250px"
                    src="/images/controlesDeVelocidad.jpg"
                  />
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <span class="title">Controles de Estacionamiento</span>
                      <div class="text-md-justify pt-3">Parts Sistemas ofrece distintas soluciones para el control urbano de estacionamiento medido. Sistema de Gestión de Estacionamiento basados en parquímetros con pago en monedas, tarjetas de crédito y monederos electrónicos, con impresión de tickets y administración remota centralizada. Y sistemas basados en telefonía celular mediante el envío y recepción de sms.</div>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <span class="title">Controles de Semáforos</span>
                      <div class="text-md-justify pt-3">Desarrollamos contadores de cuenta regresiva basados en microcontroladores inteligentes que tienen la capacidad de sincronizarse de forma automática con cualquier tipo y modelo de semáforo. Tampoco requiere acceder a la red semafórica ni programación previa de la unidad. Posee caracteres de gran tamaño basado en leds de alta luminosidad y gabinete IP65.</div>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <span class="title">Controles de Velocidad</span>
                      <div class="text-md-justify pt-3">Proveemos soluciones basadas en radares doppler que permiten detectar vehículos, contarlos, determinar su sentido y hasta medir su velocidad. A partir de esta tecnología ofrecemos productos para controlar la velocidad vehicular en calles, colegios, barrios cerrados, etc. Sistemas de información para evitar accidentes y sistemas de control de cruce con semáforo en luz roja.</div>
                    </v-card-text>
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
