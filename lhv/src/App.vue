<template>
  <v-app>
    <v-content>
      <Header/>
      <Links />
    </v-content>
    <Carousel />
  </v-app>
</template>

<script>
import Header from './components/Header'
import Links from './components/Links'
import Carousel from './components/Carousel'

export default {
  name: 'App',

  components: {
    Links,
    Carousel,
    Header
  },

  data: () => ({
    //
  })
}
</script>
