<template>
<v-app>
    <v-card
    class="mx-auto"
    max-width="450"
    tile
  >
      <v-row
        align="end"
        class="fill-height"
      >
        <v-col
          align-self="start"
          class="pa-0"
          cols="12"
        >
          <v-avatar
            class="profile"
            color="grey"
            size="164"
            tile
          >
            <v-img src="/images/david.jpg"></v-img>
          </v-avatar>
        </v-col>
        <v-col class="py-0">
          <v-list-item
            color="rgba(0, 0, 0, .4)"
            dark
          >
            <v-list-item-content>
              <v-list-item-title class="title">David Perez Ezquivel</v-list-item-title>
              <v-list-item-subtitle class="pl-2 mt-2 pr-2">Programador, corredor y nadador; tres cosas que me apasionan hacer.<br/> &nbsp;&nbsp;Programmer, runners and swimmers; three things that I love doing
              </v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-col>
      </v-row>
  </v-card>
</v-app>
</template>

<script>
export default {

}
</script>

<style>

</style>
