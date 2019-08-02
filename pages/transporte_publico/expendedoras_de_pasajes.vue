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
            src="/images/transportePublico.jpg"
          >
            <v-container
              grid-list-md
              fluid
            >
              <v-layout
                row
                wrap
              >
                <h1 class="blue-grey--text text--darken-4">Transporte Público</h1>
              </v-layout>
            </v-container>
            <v-card-actions class="mt-5 pt-5">
              <v-spacer></v-spacer>
              <menuTransportePublico />
            </v-card-actions>
          </v-img>
          <v-card-title>
            <div class="pt-3">
              <h2 class="pt-3 pl-4">Expendedoras de Pasajes</h2>
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
                    <v-card-text>
                        <p class="pl-4 pr-4">
                            <v-img src="/images/expendedoraPasajes.jpg" />
                        </p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text>
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">El constante crecimiento de usuarios del Trasporte Público demanda una mejora permanente del servicio, la atención y la velocidad de expendio de los pasajes. Lograr transacciones rápidas, seguras y fluidas se convierte en el objetivo a alcanzar y contar con equipos expendedores de última generación constituye el eslabón fundamental para lograrlo. Para Parts Sistemas cada cliente es especial y sabemos que tiene sus propios requerimientos y necesidades. Por lo tanto, diseñamos y desarrollamos una solución particular para cada uno, obteniendo un equipo a medida, con tecnología de última generación que los satisfaga plenamente. Todos los equipos se complementan con nuestro Sistemas de Ayuda a la Explotación (SAE) conformando una gran red de datos vía comunicación inalámbrica que permite monitorear, controlar y recaudar toda la información de las expendedoras, proporcionando una solución integradora y global. Nuestras expendedoras son desarrolladas para cubrir un amplio espectro de necesidades ofreciendo la mayor flexibilidad de la industria. El software ofrece una robustez, seguridad y velocidad incomparables. Además, su probada escalabilidad nos permite adaptarlo a los requerimientos mas exigentes.</p>
                    </v-card-text>
                  </v-flex>
                </v-layout>
                <v-layout
                  row
                  wrap
                >
                  <v-flex
                    d-flex
                    xs12
                    sm12
                    md12
                  >
                    <v-card-text>
                      <div class="subtitulo font-weight-bold amber--text">Nuestro Presente</div>
                      <div class="font-weight-medium">La experiencia de más de una década en el diseño, fabricación y programación de expendedoras de pasajes nos permite contar hoy con eq uipos de última generación</div>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6>
                    <v-card-text>
                      <span class="title">Validadores</span>
                      <div class="text-md-justify text-xs-justify">La nueva línea de Validadores de Pasajes ofrece, además de las características de robustez y funcionalidad ya comunes en los equipos de Parts Sistemas, un diseño pulido que no pasa desapercibido a la vista. Sus líneas simples y elegantes contrastan con su desarrollo que incorpora la tecnología más avanzada para la venta de pasajes con tarjetas sin contacto, el seguimiento de flota y la transmisión on line de toda la inf ormación generada.
                      </div>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6>
                    <v-card-text>
                      <span class="title">Teclados</span>
                      <div class="text-md-justify text-xs-justify">Nuestros teclados son diseñados y fabricados buscando la constante innovación y adaptación a los rápidos cambios tecnológicos. Ofrecemos un amplio rango de tipos teclados, desde soluciones basados en menbranas con pantallas de caracteres con retroiluminación hasta teclados touch capacitivos sin componentes mecánicos, libres de mantenimiento, resistentes al polvo y el agua y con pantallas gráficas color.
                      </div>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm12
                    md12>
                    <div class="display-1 text-md-center text-xs-center text-sm-center pt-4 pb-4 amber white--text">Todas las prestaciones en un solo equipo</div>
                  </v-flex>
                  <v-card-text>
                    <p class="pl-4 pr-4">
                        <v-img src="/images/expendedoraPasajes_2.jpg" contain height="250" />
                    </p>
                  </v-card-text>
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
import menuTransportePublico from '~/components/menuTransportePublico';
export default {
  components:{
    menuTransportePublico
  },
  head: {
    title: 'Transporte Público - Expendedoras de Pasajes'
  }
};
</script>

<style scoped>
.subtitulo {
  font-family: "Ubuntu";
  font-size: 2.5vw;
}
p::first-letter {
  font-weight: bold;
  color: #ffab00;
  font-size: 18px;
}
</style>
