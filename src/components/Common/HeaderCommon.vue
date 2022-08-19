<template>
  <v-card
    color="grey lighten-4"
    flat
    height="200px"
    tile
  >
    <v-toolbar dense>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-toolbar-title>
        {{ headerData }}
      </v-toolbar-title>

    <v-spacer></v-spacer>

    <btn-common icon>
        <v-icon>mdi-magnify</v-icon>
      </btn-common>

      <btn-common icon>
        <v-icon>mdi-heart</v-icon>
      </btn-common>

      <btn-common icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </btn-common>
      
    </v-toolbar>
  </v-card>
</template>

<script>
import vue from 'vue'
// components
import BtnCommon from '@/components/Common/BtnCommon.vue'

export default vue.extend({ 
  props: [
    'headerData'
  ],

  components: {
    BtnCommon,
  },
})
</script>
