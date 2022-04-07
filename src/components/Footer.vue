<template>
  <v-footer
    class="align-center justify-center column"
    dark
    padless
  >
    <v-card
      flat
      tile
      class="indigo lighten-1 white--text text-center"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4 white--text"
          :href="icon.link"
          
        >
          <v-icon size="32px">
            {{ icon.logo }}
          </v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
        Hello! 👋, my name is Kirill Zagul. I'm a web developer living in Tyumen, programming in JavaScript and Vue.js      
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong>Kirill Zagul</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
  export default {
    data: () => ({
      icons: [
        {
          logo: 'mdi-alpha-h',
          link: 'https://career.habr.com/zagulkirill'
        },
        {
          logo: 'mdi-telegram',
          link: 'https://t.me/zakneo',
        },
        {
          logo:  'mdi-github',
          link: 'https://github.com/kzagul',
        },
        {
          logo:  'mdi-vk',
          link: 'https://vk.com/killrealthecool',
        }
      
      ],
    }),
  }
</script>

<style scoped>
.v-card-text{
  font-size: 28px;
  line-height: 2em;
  font-family: Orbitron, Arial, Helvetica, sans-serif;
}
</style>
