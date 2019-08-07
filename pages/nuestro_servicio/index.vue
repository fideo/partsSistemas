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
            src="/images/nuestroServicio.jpg"
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
                  <h1 class="blue-grey--text text--darken-4 sombraBlanca">Nuestro Servicio</h1>
                </v-flex>
              </v-layout>
            </v-container>
          </v-img>
          <v-card-title>
            <div class="pt-3">
              <h2 class="pt-3 pl-4">Muchos piensan que la concreción de una exitosa operación comercial es el objetivo final buscado por una empresa. En Parts Sistemas creemos firmemente que esa no es la meta, sino el punto de partida de una larga relación junto a nuestros clientes</h2>
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
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">Nacidos como una empresa con una fuerte orientación de servicio al cliente y nos preocupamos por satisfacer todas sus necesidades desde el primer momento, pero nuestra meta, por sobre todo, es poder brindar todos los beneficios posteriores a la venta que aseguraren su inversión en el tiempo, garantizando la calidad y servicio de los productos ofrecidos.<br/>
                      <br>El objetivo de nuestro departamento de servicio post venta es ayudar a los clientes a maximizar su eficiencia manteniendo los sistemas en un nivel óptimo de productividad y solucionando los inconvenientes con la mayor celeridad posible.</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm6
                    md6
                  >
                    <v-card-text class="px-0">
                      <p class="pl-4 pr-4 text-md-justify text-xs-justify">Contamos con contratos de servicios de mantenimiento que se originaron hace más de 10 años y se renuevan año a año. Nuestro compromiso se ve reflejado en la fidelidad de nuestros clientes, quienes renuevan su confianza en nuestra empresa y servicios.<br>
                      <br>El equipo de profesionales de Ingeniería y técnicos tienen el conocimiento y experiencia para brindar un servicio al cliente de primer nivel. Ofrecemos distintos tipos de servicios de mantenimiento dependiendo de sus necesidades. Desde la provisión de repuestos y soporte telefónico hasta la presencia in situ 24/7.</p>
                    </v-card-text>
                  </v-flex>
                  <v-flex
                    d-flex
                    xs12
                    sm12
                    md12>
                    <div class="display-1 text-md-center text-xs-center text-sm-center pt-4 pb-4 amber white--text">NUESTRO COMPROMISO, <br>garantizar su inversión en el tiempo</div>
                  </v-flex>
                </v-layout>
              </v-container>
            </div>
          </v-card-title>
          <v-img
            class="white--text"
            height="250px"
            src="/images/nuestroServicio_2.jpg"
          ></v-img>
        </v-card>
      </v-flex>
    </v-layout>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Nuestro Servicio'
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
