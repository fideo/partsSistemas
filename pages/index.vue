<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <div class="text-xs-center">
        <parts-sistemas-logo />
      </div>
      <div class="text-xs-center">
        <logo />
      </div>
      <div class="mt-3">
        <h1>
          Nos complace saber que está interesado en nuestra compañía y queremos proporcionarle información sobre nuestras soluciones, productos y servicios
        </h1>
        <h4 class="mt-3">
          Fundada en 1978, Parts S.A. es una compañia de capitales Argentinos que ha desarrollado su actividad Industrial y Comercial en forma ininterrumpida desde esa fecha a la actualidad. Como fruto de nuestro constante desarrollo a lo largo del tiempo, hemos incremenentado la capacidad productiva y de crecimiento, expandiéndonos y diversificándonos, dando origen a nuevas áreas y divisiones. En la actualidad contamos con 3 compañias que brindan soluciones, productos y servicios a más de 1.400 clientes en las áreas Metalúrgica, Fundición y Tecnología.
        </h4>
      </div>
    </v-flex>
  </v-layout>
</template>

<script>
import PartsSistemasLogo from '~/components/PartsSistemasLogo.vue'
import Logo from '~/components/Logo.vue'

export default {
  components: {
    PartsSistemasLogo,
    Logo
  }
}
</script>
