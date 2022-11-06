<template>
 <v-app>
  <NavBar class="index"/>
  <Dashboard />
  <Footer />
 </v-app>
</template>

<script>
  import NavBar from '../components/NavBar'
  import Dashboard from '../components/Dashboard'
  import Footer from '../components/Footer'
  export default {
    name: 'Home',

    components: {
      NavBar,
      Dashboard,
      Footer
    },
  }
</script>
<style scoped>
.index {
  z-index: 9999;
}
</style>
