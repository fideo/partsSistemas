<template>
<div>
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
    sm4
    md4
  >
    <v-card
      class="mx-auto"
      max-width="400"
      to="/nuestro_enfoque"
    >
      <v-img
        class="white--text"
        height="200px"
        src="/images/nuestroEnfoque.jpg"
      >
        <v-card-title class="align-end fill-height flex display-1 font-weight-bold sombra">Enfoque</v-card-title>
      </v-img>
    </v-card>
  </v-flex>
  <v-flex
    d-flex
    xs12
    sm4
    md4
  >
    <v-card
      class="mx-auto"
      max-width="400"
      to="/nuestro_servicio"
    >
      <v-img
        class="white--text"
        height="200px"
        src="/images/nuestroServicio.jpg"
      >
        <v-card-title class="align-end fill-height flex display-1 font-weight-bold sombra">Servicio</v-card-title>
      </v-img>
    </v-card>
  </v-flex>
  <v-flex
    d-flex
    xs12
    sm4
    md4
  >
  <v-card
    class="mx-auto"
    max-width="400"
    to="/nuestro_mercado"
  >
    <v-img
      class="white--text"
      height="200px"
      src="/images/transporteVehicular.jpg"
    >
      <v-card-title class="align-end fill-height flex display-1 font-weight-bold sombra">Mercado</v-card-title>
    </v-img>
  </v-card>
  </v-flex>
    </v-layout>
  </v-container>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.sombra {
  text-shadow: -2px 2px 4px black;
}
</style>
