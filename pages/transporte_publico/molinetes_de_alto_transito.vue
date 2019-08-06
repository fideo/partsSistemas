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
              <h2 class="pt-3 pl-4">Molinetes de Alto Tránsito</h2>
              <h4 class="pt-3 pl-4 pr-4">Parts Sistemas diseña molinetes pensados para trabajar en entornos muy exigentes, de uso intensivo y con altos requerimientos mecánicos y funcionales</h4>
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
                    sm12
                    md12
                  >
                    <v-card-text>
                        <p class="pl-4 pr-4">
                            <v-img src="/images/molinetesAltoTransito.jpg" max-height="250" />
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
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">Nuestros molinetes, desarrollados integramente en acero inoxidable y con un cuidado diseño, son capaces de soportar altos caudales de personas debido a que son fabricados principalmente para su uso en el Transporte Público de Pasajeros. Cuentan con un mecanismo de tres aspas, software de control totalmente configurable de acuerdo a las necesidades del usuario y un sistema remoto de administración.</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text>
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">El giro de las aspas, en situación normal, es libre y los dispositivos electromecánicos de control actúan solamente en caso de un intento de paso no autorizado, minimizando el consumo eléctrico y alargando la vida útil de toda la mecánica asociada. Su diseño modular, incluso del rotor principal, ofrece la versatilidad de poder efectuar un rápido reemplazo de cualquier componente del equipo en su lugar de trabajo.</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <span class="title">Características Principales</span>
                      <ul class="pt-3">
                        <li>Construido en acero inoxidable</li>
                        <li>Mecanismo de alta durabilidad</li>
                        <li>Amortiguador fin de recorrido</li>
                        <li>Aspas de acero inoxidable</li>
                        <li>Sentido de paso configurable</li>
                        <li>Sistema antivandalismo</li>
                        <li>Sistema antipánico</li>
                        <li>Alarmas configurables</li>
                        <li>Rotor central montado sobre rodamientos blindados y autolubricados</li>
                      </ul>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <span class="title">Ventajas Competitivas</span>
                      <ul class="pt-3">
                        <li>Diseñado para uso intensivo</li>
                        <li>Alta velocidad de operación</li>
                        <li>Excelente Robustez</li>
                        <li>Electrónica altamente probada</li>
                        <li>Mecánica de rápido reemplazo</li>
                        <li>Alta resistencia a los golpes</li>
                        <li>Apto para uso a la intenperie</li>
                        <li>Libre de mantenimiento</li>
                        <li>Facilidad de integración con lectores de tarjetas sin contacto y lectores de tipo biométrico</li>
                      </ul>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <span class="title">Soft de Administración</span>
                      <div class="text-md-justify text-xs-justify pt-3">Nuestro Sistema de Ayuda a la Explotación (SAE) permite administrar y monitorear todo su equipamiento, sin importar la variedad, cantidad y diversidad de los equipos que lo compongan, desde un único centro de control. Permite realizar ABMs de los equipos, controlar accesos, configurar los sentidos de paso, alarmas y mucho más.</div>
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
import menuTransportePublico from '~/components/menuTransportePublico' ;
export default {
  components: {
    menuTransportePublico
  },

  head: {
    title: 'Transporte Público - Expendedoras de Pasajes'
  }
};
</script>

<style scoped>
p::first-letter {
  font-weight: bold;
  color: #ffab00;
  font-size: 18px;
}
</style>
