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
            src="/images/nuestroEnfoque.jpg"
          >
            <v-container
              grid-list-md
              fluid
            >
              <v-layout fill-height>
                <v-flex
                  xs12
                  align-end
                  flexbox
                >
                  <h1 class="white--text text--darken-4">Nuestro Enfoque</h1>
                </v-flex>
              </v-layout>
            </v-container>
            <v-card-actions class="mt-5 pt-5">
            <v-spacer></v-spacer>
            <menuEnfoServMerc />
            </v-card-actions>
          </v-img>
          <v-card-title>
            <div class="pt-3">
              <h2 class="pt-3 pl-4">Parts Sistemas desarrolla Soluciones de Ingeniería a medida de las necesidades de cada cliente basadas en tecnologías de última generación probad as y sustentables</h2>
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
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">Nuestro objetivo es proveer una solución original a cada requerimiento basada en nuestra experiencia y en función de sus necesidades. Consideramos que cada situación es distinta y particular, por lo cual, debe ser relevada, analizada y diagnosticada correctamente para poder brindar una verdadera solución de valor que sea ef icaz y efectiva en el tiempo.</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text>
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">Para brindar estas respuestas, Parts Sistemas cuenta con un equipo de profesionales formado por Ingenieros en Sistemas, Ingenieros Industriales, técnicos electrónicos y técnicos mecánicos que comparten el mismo compromiso y espíritu de ofrecer cada día toda su capacidad y esfuerzo para lograr la plena satisfacción de nuestros clientes.</p>
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
import menuEnfoServMerc from '~/components/menuEnfoServMerc'
export default {
  components:{
    menuEnfoServMerc
  },
  head: {
    title: 'Nuestro Enfoque'
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
