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
            src="/images/banking.jpg"
          >
            <v-container
              grid-list-md
              fluid
            >
              <v-layout 
              row
              wrap
              >
                <h1 class="blue-grey--text text--darken-4 sombraBlanca">Banking</h1>
              </v-layout>
            </v-container>
            <v-card-actions class="mt-5 pt-5">
              <v-spacer></v-spacer>
              <menuBanking />
            </v-card-actions>
          </v-img>
          <v-card-title>
            <div class="pt-3">
              <h2 class="pt-3 pl-4">Parts Sistemas provee una gran variedad de terminales de atención que satisfacen los requerimientos de cada cliente soportando las aplicaciones más diversas</h2>
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
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">La amplia gama de terminales que ofrecemos incluye: Terminales de auto atención y consulta, Equipos de depósito de valores y manejo de efectivo, Terminales de punto de venta, Kioskos de entrega de turnos, Equipos de cobranzas y recaudaciones, Módulos de cartelería digital y Vidrieras interactivas. Además, ofrecemos la posibilidad de adaptar modelos existentes o desarrollar equipos totalmente nuevos a requerimiento de nuestros clientes</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text class="px-0">
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">Toda la fabricación de las terminales se lleva a cabo bajo certificación de estándares ISO 9001-2008 en procesos productivos. Todos los equipos cuentan con certificaciones en seguridad eléctrica y cumplen con los estándares de la directiva RoHS. Todas las terminales se ofrecen bajo la modalidad de plataforma de software abierto, esto significa que cada cliente puede desarrollar su propia aplicación, instalar la de un tercero o solicitar su desarrollo a Parts Sistemas</p>
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
                    max-height="300px"
                    contain
                    src="/images/terminalAutogestion.jpg"
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
                    height="300px"
                    contain
                    src="/images/equiposGestionDeValor.jpg"
                  />
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4
                  ><v-img
                    class="white--text"
                    height="300px"
                    contain
                    src="/images/carteleriasInteractivas.jpg"
                  />
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <span class="title">Terminales de Autogestión</span>
                      <div class="text-md-justify pt-3">
                        <strong>Características Principales:</strong>
                        <ul>
                          <li>Monitor táctil</li>
                          <li>Teclado anti vandálico</li>
                          <li>Impresora térmica</li>
                        </ul>
                        <br>
                        <strong>Opcionales:</strong>
                        <ul>
                          <li>Lector de tarjetas</li>
                          <li>Lector de código de barras</li>
                          <li>Lector de código de manchas</li>
                          <li>Lectores biométricos</li>
                          <li>Validador de billetes</li>
                          <li>Dispensador de tarjetas</li>
                          <li>Otros</li>
                        </ul>
                      </div>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <span class="title">Equipos de Gestión de Valor</span>
                      <div class="text-md-justify pt-3">
                        <strong>Ofrecemos varios modelos:</strong>
                        <ul>
                          <li>Cash Dispenser</li>
                          <li>Cajero Full</li>
                          <li>Terminales de depósito</li>
                        </ul>
                        <br>
                        <strong>Características comunes:</strong>
                        <ul>
                          <li>Monitor táctil</li>
                          <li>Impresora térmica</li>
                          <li>Lector de tarjetas</li>
                          <li>Teclado anti vandálico</li>
                          <li>Cofre de seguridad</li>
                          <li>Gabinete de alta seguridad</li>
                          <li>Conexión a red</li>
                        </ul>
                      </div>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <span class="title">Cartelerías Interactivas</span>
                      <div class="pt-3">
                        <strong>Características Principales:</strong>
                        <ul>
                          <li>Monitores LED especiales</li>
                          <li>Tecnología LFD</li>
                          <li>Desde 32” hasta 46”</li>
                          <li>Nano Touch o IR Touch</li>
                          <li>CPU Industrial</li>
                        </ul>
                        <br>
                        <strong>Opcionales:</strong>
                        <ul>
                          <li>Impresora térmica</li>
                          <li>Lector de tarjetas</li>
                          <li>Lector de código de barras</li>
                          <li>Lector de código de manchas</li>
                          <li>Modem GPRS y/o WiFi</li>
                        </ul>
                      </div>
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
import menuBanking from '~/components/menuBanking'
export default {
  components: {
    menuBanking
  },
  head: {
    title: 'Banking'
  }
};
</script>

<style scoped>
p::first-letter {
  font-weight: bold;
  color: #ffab00;
  font-size: 18px;
}
.sombra {
  text-shadow: -2px 2px 4px white;
}
</style>
