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
                <h1 class="blue-grey--text text--darken-4">Nuestro Mercado</h1>
              </v-layout>
            </v-container>
            <v-card-actions class="mt-5 pt-5">
              <v-spacer></v-spacer>
              <menuTransitoVehicular />
            </v-card-actions>
          </v-img>
          <v-card-title>
            <div class="pt-3">
              <h2 class="pt-3 pl-4">Parts Sistemas es el lider tecnológico de la región en la provisión de Expendedoras de Pasajes para boleterías y el desarrollo de Molinetes de Alto Tránsito para ferrocariles</h2>
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
                    x12
                    sm4
                    md4
                  >
                  <v-img
                    class="white--text"
                    src="/images/expendedoras.jpg"
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
                    src="/images/molinetes.jpg"
                  />
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4
                  ><v-img
                    class="white--text"
                    src="/images/recargaTSC.jpg"
                  />
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <div class="headline text-sm-center text-md-center text-lg-center text-xl-center">Expendedoras</div>
                      <div class="display-3 text-sm-center text-md-center text-lg-center text-xl-center">78%<br/></div>
                      <div class="title text-sm-center text-md-center text-lg-center text-xl-center">Parts Sistemas</div>
                      <div class="text-md-justify pt-3">El 78 porciento de los equipos de punto de Venta de Pasajes y Recarga de Tarjetas sin Contacto de las boleterías de ferrocarriles de nuestro país son expendoras de pasajes que han sido diseñadas y fabricadas por nuestra empresa</div>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <div class="headline text-sm-center text-md-center text-lg-center text-xl-center">Molinetes</div>
                      <div class="display-3 text-sm-center text-md-center text-lg-center text-xl-center">75%<br/></div>
                      <div class="title text-sm-center text-md-center text-lg-center text-xl-center">Parts Sistemas</div>
                      <div class="text-md-justify pt-3">El 75 porciento de los molinetes de las líneas ferroviarias de nuestro país han sido desarrollados por Parts Sistemas. Más de 1.400 equipos diseñados para soportar un gran caudal de usuarios y más de 450 equipos reacondicionados</div>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    x12
                    sm4
                    md4>
                    <v-card-text>
                      <div class="headline text-sm-center text-md-center text-lg-center text-xl-center">Recarga TSC</div>
                      <div class="display-3 text-sm-center text-md-center text-lg-center text-xl-center">81%<br/></div>
                      <div class="title text-sm-center text-md-center text-lg-center text-xl-center">Parts Sistemas</div>
                      <div class="text-md-justify pt-3">El 81 porciento de las operaciones de Venta y Recarga de Tarjeta sin contacto del Sistema Único de Boleto Electrónico se realiza a través de nuestros POS. El volumén de transacciones mensuales realizadas superan los 18.000.000</div>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm12
                    md12>
                    <div class="display-1 text-md-center text-xs-center text-sm-center pt-4 pb-4 blue white--text">78% Participación Promedio Mercado</div>
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
    title: 'Nuestro Mercado'
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
