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
              fill-height
              fluid
            >
              <v-layout fill-height>
                <v-flex
                  xs12
                  align-end
                  flexbox
                >
                  <h1 class="blue-grey--text text--darken-4">Banking</h1>
                </v-flex>
              </v-layout>
            </v-container>
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
                      <p class="pl-4 pr-4">La amplia gama de terminales que ofrecemos incluye: Terminales de auto atención y consulta, Equipos de depósito de valores y manejo de efectivo, Terminales de punto de venta, Kioskos de entrega de turnos, Equipos de cobranzas y recaudaciones, Módulos de cartelería digital y Vidrieras interactivas. Además, ofrecemos la posibilidad de adaptar modelos existentes o desarrollar equipos totalmente nuevos a requerimiento de nuestros clientes</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text class="px-0">
                      <p class="pl-4 pr-4">Toda la fabricación de las terminales se lleva a cabo bajo certificación de estándares ISO 9001-2008 en procesos productivos. Todos los equipos cuentan con certificaciones en seguridad eléctrica y cumplen con los estándares de la directiva RoHS. Todas las terminales se ofrecen bajo la modalidad de plataforma de software abierto, esto significa que cada cliente puede desarrollar su propia aplicación, instalar la de un tercero o solicitar su desarrollo a Parts Sistemas</p>
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
export default {};
</script>

<style scoped>
p::first-letter {
  font-weight: bold;
  color: #ffab00;
  font-size: 18px;
}
</style>
