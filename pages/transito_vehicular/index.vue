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
              fill-height
              fluid
            >
              <v-layout fill-height>
                <v-flex
                  xs12
                  align-end
                  flexbox
                >
                  <h1 class="blue-grey--text text--darken-4">Tránsito Vehicular</h1>
                </v-flex>
              </v-layout>
            </v-container>
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
                      <p class="pl-4 pr-4">Comenzamos desarrollando sistemas de estacionamiento medido mediante parquímetros y luego incorporamos sistemas de registración de estacionamiento mediante telefonía celular. Posteriormente incursionamos en el mercado semafórico desarrollando contadores de cuenta regresiva inteligentes que se adaptan automaticamente a la red semafórica existente y no necesitan preprogramación</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text class="px-0">
                      <p class="pl-4 pr-4">Actualmente estamos ofreciendo sistemas de control de tránsito de última generación basados en radares que permiten detectar excesos de velocidad, invasión de senda peatonal y cruce de semáforos con luz roja. Así mismo, estamos presentando el nuevo Sistema de Advertencia Temprana de Intersecciones Vehiculares basado también en tecnología no intrusiva</p>
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
export default {
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
