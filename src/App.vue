<template>
  <v-app id="inspire">
    <v-navigation-drawer
      v-model="drawer"
      app
    >
    </v-navigation-drawer>
    <!-- ƒwƒbƒ_[ -->
    <VHeaderCommon :header="vHeader"></VHeaderCommon>

    <v-main>
      <!--  -->
    </v-main>
  </v-app>
</template>

<script>
  import vue from 'vue'
  // components
  import VHeaderCommon from './components/Common/VHeaderCommon.vue'

  export default vue.extend({
    components: {
      VHeaderCommon
    },
    data() {
      return {
        vHeader: {
          title: 'SampleTitle',
        },
        drawer: false
      }
    }
  }) 
</script>