<template>
  <div id="app">
    <nav-bar></nav-bar>
    <router-view></router-view>

  </div>
</template>

<script>
import Vue from 'vue'
import BootstrapVue from 'bootstrap-vue'

Vue.use(BootstrapVue);
import navBar from "./components/navBar.vue"
import footer from "./components/footer.vue"

export default {
  components: {
    'navBar': navBar,
    'app-footer': footer

  },
  data() {
    return {


    }
  },

}
</script>

<style scoped>


</style>