<template>
  <v-app id="inspire">
    <v-navigation-drawer
      v-model="drawer"
      app
    >
    </v-navigation-drawer>
    <!-- ヘッダー -->
    <header-common
      :header-data="vHeader"
    >

    </header-common>
    
    <v-main>
      <!--  -->
    </v-main>
  </v-app>
</template>

<script>
  import vue from 'vue'
  // components
  import HeaderCommon from './components/Common/HeaderCommon.vue'


  export default vue.extend({
    components: {
      HeaderCommon,
    },
    data() {
      return {
        vHeader: 'SampleTitle',
        drawer: false,
      }
    }
  }) 
</script>