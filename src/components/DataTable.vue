<template>
  <v-data-table
    v-baind="$attrs"
    :items="items"
    :headers="headerList"
    :items-per-page="limit"
    :footer-props="footerProps"
    @click:row="pageingClicked"
  ></v-data-table>

</template>
<script lang="ts">

import { Vue, Component, Emit, Watch} from 'vue-property-decorator'

export default Vue.extend({
  
})
</script>

