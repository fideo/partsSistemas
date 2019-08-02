<template>
  <div>
    <no-ssr>
      <v-navigation-drawer
        v-model="drawer"
        fixed
        temporary
        class="lighten-2"
      >
        <v-list>
          <v-list-tile
            v-for="item in menu"
            :key="item.title"
            :to="item.link"
          >
            <v-list-tile-action>
              <v-icon>{{ item.icon }}</v-icon>
            </v-list-tile-action>
            <v-list-tile-content>
              <v-list-tile-title>{{ item.title }}</v-list-tile-title>
            </v-list-tile-content>
          </v-list-tile>
        </v-list>
      </v-navigation-drawer>
      <v-toolbar
        app
        fixed
        class="yellow accent-4"
      >
        <v-spacer></v-spacer>
        <v-btn
          color="blue"
          dark
          @click.stop="drawer = !drawer"
          class="hidden-md-and-up"
        >
          Menú
        </v-btn>
        <v-toolbar-items class="hidden-sm-and-down">
          <v-btn
            v-for="item in menu"
            :key="item.title"
            :to="item.link"
            flat
          >
            <v-list-tile>{{item.title}}</v-list-tile>
          </v-btn>
        </v-toolbar-items>
        <v-spacer></v-spacer>
      </v-toolbar>
    </no-ssr>
  </div>
</template>

<script>
export default {
  data: () => ({
    drawer: null,
    menu: [
      { title: "Inicio", icon: "home", link: "/" },
      {
        title: "Transporte Público",
        icon: "directions_subway",
        link: "../transporte_publico/"
      },
      {
        title: "Tránsito Vehicular",
        icon: "directions_car",
        link: "../transito_vehicular/"
      },
      {
        title: "Banking",
        icon: "account_balance",
        link: "../banking/"
      },
      {
        title: "Control de Acceso",
        icon: "vpn_key",
        link: "../control_de_acceso/"
      }
    ]
  })
};
</script>

<style  scoped>
.v-btn--active {
  color: gray
}
</style>
