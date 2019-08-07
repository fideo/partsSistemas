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
                <h1 class="blue-grey--text text--darken-4">Banking</h1>
              </v-layout>
            </v-container>
            <v-card-actions class="mt-5 pt-5">
              <v-spacer></v-spacer>
              <menuBanking />
            </v-card-actions>
          </v-img>
          <v-card-title>
            <div class="pt-3">
              <h2 class="pt-3 pl-4">Q-Parts</h2>
              <h4 class="pt-3 pl-4 pr-4">Q-Parts es una solución diseñada para la administración del flujo de sus clientes y la gestión de los tiempos de espera y atenció n</h4>
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
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">Todos sabemos que el cliente es lo más importante. Con esa premisa en mente desarrollamos Q-Parts. Un sistema que permite brindar a sus clientes una mejor experiencia mientras esperan relajados por ser atendidos. Q-Parts organiza la atención a la vez que acompaña sus clientes con información, videos y publicidad, haciendo la espera más amena y evitando la necesidad de tediosas filas y colas de espera.</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text class="px-0">
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">El conjunto de soluciones de Q-Parts sa-tisface todas las necesidades de su negocio. Se adapta facilmente a cualquier tipo de actividades, como, Banca, Salud, Educación, Venta al público, Gobierno, Seguros, Correo. Cuenta con módulos personalizables de recepción, atención, gestión on-line, señalización, workflow, información estadística de tiempos de espera, tiempos de atención, tiempos ociosos, etc.</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                  xs12
                  sm6
                  md6
                  >
                  <v-img src="/images/controlDeTurnos.jpg"/>
                  </v-flex>
                  <v-flex
                  xs12
                  sm6
                  md6
                  font-weight-bold
                  pl-3 pr-3 pb-3 pt-4
                  >
                  <p>Optimiza el flujo de sus clientes, elimina esperas innecesarias y trabas</p>
                  <p>Mide en tiempo real el flujo de clientesa través de su organización.</p>
                  <p>Administra la recepción, atención, colas y turnos.</p>
                  <p>Facilita el monitoreo, análisis, control y corrección.</p>
                  <p>Genera estadísticas e informes.</p>
                  <p>Permite enviar mensajes entre los puestos de atención y el servidor.</p>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm12
                    md12>
                    <div class="display-1 text-md-center text-xs-center text-sm-center pt-4 pb-4 amber white--text">Beneficios</div>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                    mt-4
                  >
                    <v-btn color="warning" fab dark small>
                      <v-icon>thumb_up</v-icon>
                    </v-btn>
                    <span class="caption "> Mejora la calidad de servicio y atención</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                    mt-4
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>reorder</v-icon>
                  </v-btn>
                    <span class="caption "> Optimiza y Organiza sus recursos</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>favorite</v-icon>
                  </v-btn>
                    <span class="caption "> Resalta la imagen corporativa de su empresa</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>hourglass_full</v-icon>
                  </v-btn>
                    <span class="caption "> Produce una percepción de un menor tiempo de espera</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>group</v-icon>
                  </v-btn>
                    <span class="caption "> Libera a sus clientes de la necesidad de formar filas</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>stars</v-icon>
                  </v-btn>
                    <span class="caption "> Enriquece la experiencia de usuarios y empleados</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>info</v-icon>
                  </v-btn>
                    <span class="caption "> Entretiene a sus clientes mientras esperan ser atendidos</span>
                  </v-flex>
                  <v-flex
                    xs12
                    sm6
                    md6
                  >
                  <v-btn color="warning" fab dark small>
                    <v-icon>visibility</v-icon>
                  </v-btn>
                    <span class="caption "> Supervisa, resuelve y perfecciona la gestión</span>
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
import menuBanking from '~/components/menuBanking';
export default {
  components: {
    menuBanking
  },
  head:{
    title: 'Q-Parts - Banking '
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
