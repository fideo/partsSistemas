<template>
  <v-app>

    <Menu />
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer
      :fixed="fixed"
      app
      class="footer"
    >
      <v-flex text-xs-center>
        <span><strong>&copy; 2019 - Parts Sistemas </strong>- Buenos Aires - Argentina - Tel: <a
            class="link"
            href="tel:+54 11 4758 7300"
          >+54 11 4758 7300</a><a
            class="link"
            href="tel:+54 11 4758 7400"
          >/7400</a><a
            class="link"
            href="tel:+54 11 4758 7600"
          >/7600</a>
          E-mail: <a
            class="link"
            href="mailto:ventas@partssistemas.com.ar?subject=Enviado desde el sitio web&body=este es el cuerpo"
          >ventas@partssistemas.com.ar</a></span>
      </v-flex>
    </v-footer>
  </v-app>
</template>

<script>
import Menu from "~/components/Menu.vue";
export default {
  components: {
    Menu
  },
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: "apps",
          title: "Welcome",
          to: "/"
        },
        {
          icon: "bubble_chart",
          title: "Inspire",
          to: "/inspire"
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Vuetify.js"
    };
  }
};
</script>
<style scoped>
.link {
  color: inherit;
  text-decoration: none;
}
.link:hover {
  text-decoration: underline;
}
.footer {
  background-color: lightgray;
}
@media (max-width: 780px) {
  .footer {
    background-color: lightgray;
    padding: 2.5em;
  }
}
</style>
