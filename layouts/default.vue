<template>
  <v-app>

    <Menu/>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer
      :fixed="fixed"
      app
    >
    <v-flex
    text-xs-center
    >
      <span>&copy; 2019 - Parts Sistemas - Buenos Aires - Argentina</span>
    </v-flex>
    </v-footer>
  </v-app>
</template>

<script>
import Menu from '~/components/Menu.vue'
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
          icon: 'apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'bubble_chart',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
