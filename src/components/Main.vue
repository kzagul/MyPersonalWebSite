<template>
  <v-container class="align-center justify-center column">
        <v-row justify="center"  class="text-center">
        <v-avatar size="360">
        <img
            src="https://avatars.githubusercontent.com/u/36849711?v=4"
            alt="Kirill"
        >
        </v-avatar>
        </v-row>
  </v-container>
</template>

<script>

export default {
  name: 'HelloWorld',

  data: () => ({

  }),
}
</script>


<style>

.v-container{
    margin-top: 60px;
}

.v-avatar > img {
    border-radius: 50%;
}

p{
    font-family: Orbitron;
}

</style>