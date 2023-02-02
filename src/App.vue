<template>
  <div id="app">
     <app-header></app-header>
     <app-ninja></app-ninja>
     <app-footer></app-footer>
     
  </div>
</template>

<script>
import header from './components/component_header.vue'
import footer from './components/component_footer.vue'
import ninja from './components/component_ninja.vue'

export default {
  components:{
    "app-header":header,
    "app-footer":footer,
    "app-ninja":ninja


  },
  data(){
    return {
         
    }
  }
}
</script>

<style scoped>

</style>
