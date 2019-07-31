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
              <v-btn color="primary">Expendedoras de pasajes</v-btn>
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
                      <p class="pl-4 pr-4 text-md-justify">El constante crecimiento de usuarios del Trasporte Público demanda una mejora permanente del servicio, la atención y la velocidad de expendio de los pasajes. Lograr transacciones rápidas, seguras y fluidas se convierte en el objetivo a alcanzar y contar con equipos expendedores de última generación constituye el eslabón fundamental para lograrlo. Para Parts Sistemas cada cliente es especial y sabemos que tiene sus propios requerimientos y necesidades. Por lo tanto, diseñamos y desarrollamos una solución particular para cada uno, obteniendo un equipo a medida, con tecnología de última generación que los satisfaga plenamente. Todos los equipos se complementan con nuestro Sistemas de Ayuda a la Explotación (SAE) conformando una gran red de datos vía comunicación inalámbrica que permite monitorear, controlar y recaudar toda la información de las expendedoras, proporcionando una solución integradora y global. Nuestras expendedoras son desarrolladas para cubrir un amplio espectro de necesidades ofreciendo la mayor flexibilidad de la industria. El software ofrece una robustez, seguridad y velocidad incomparables. Además, su probada escalabilidad nos permite adaptarlo a los requerimientos mas exigentes.</p>
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
