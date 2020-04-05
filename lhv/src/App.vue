<template>
  <v-app>
    <v-content>
      <Header />
      <News />
      <Links />
    </v-content>
    <Carousel />
  </v-app>
</template>

<script>
import Header from './components/Header'
import Links from './components/Links'
import Carousel from './components/Carousel'
import News from './components/News'

export default {
  name: 'App',

  components: {
    Links,
    Carousel,
    Header,
    News
  },

  data: () => ({
    //
  })
}
</script>
