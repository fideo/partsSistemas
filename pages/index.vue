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
        <h1 class="text-xs-center text-sm-center text-md-center text-lg-center text-xl-center">
          Nos complace saber que está interesado en nuestra compañía y queremos proporcionarle información sobre nuestras soluciones, productos y servicios
        </h1>
        <SubMenu />
        <p class="mt-3 text-xs-justify text-sm-justify text-md-justify text-lg-justify text-xl-justify">
          Parts Sistemas S.A. desarrolla y provee soluciones tecnológicas de ingeniería y productos de última generación para dar respuesta a distintas necesidades. Nacimos como una empresa orientada a dar soluciones a necesidades del transporte público de pasajeros de nuestro país y logramos convertirnos en líderes del mercado tecnológico ferroviario. Gracias a una incondicional tradición de servicio al cliente, hoy estamos orgullosos de ofrecer productos y servicios en otras areas como tránsito, banking y control de acceso.
        </p>
        <p class="mt-3 text-xs-justify text-sm-justify text-md-justify text-lg-justify text-xl-justify">
          Fundada en 1978, Parts S.A. es una compañia de capitales Argentinos que ha desarrollado su actividad Industrial y Comercial en forma ininterrumpida desde esa fecha a la actualidad. Como fruto de nuestro constante desarrollo a lo largo del tiempo, hemos incremenentado la capacidad productiva y de crecimiento, expandiéndonos y diversificándonos, dando origen a nuevas áreas y divisiones. En la actualidad contamos con 3 compañias que brindan soluciones, productos y servicios a más de 1.400 clientes en las áreas Metalúrgica, Fundición y Tecnología.
        </p>
        <p class="mt-3 text-xs-justify text-sm-justify text-md-justify text-lg-justify text-xl-justify">
          Parts Sistemas es la compañía del Grupo dedicada al diseño, desarrollo y fabricación de soluciones tecnológicas y surgió como respuesta a necesidades del sector ferroviario de nuestro país. Actualmente brindamos soluciones tecnológicas en varios mercados y queremos invitarlos a que conozcan algunas de las mismas. Estamos convencidos que nuestro crecimiento es producto de la calidad de los productos y el objetivo de superar las expectativas de nuestros clientes. Por eso, mantenemos el compromiso de brindar la mejor solución a su requerimiento.
        </p>
      </div>
    </v-flex>
  </v-layout>
</template>

<script>
import PartsSistemasLogo from "~/components/PartsSistemasLogo.vue";
import Logo from "~/components/Logo.vue";
import SubMenu from '~/components/SubMenu';

export default {
  head:{
    title: 'Parts Sistemas'
  },
  components: {
    PartsSistemasLogo,
    Logo,
    SubMenu
  }
};
</script>
