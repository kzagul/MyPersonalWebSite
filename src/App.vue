<template>
  <v-app >
    <v-main >
      <Main />
    </v-main>
  </v-app>
  <Footer />
</template>

<script>
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',

  components: {
    Main,
    Footer
  },

  data: () => ({
    //
  }),
}
</script>

<style scoped>

</style>