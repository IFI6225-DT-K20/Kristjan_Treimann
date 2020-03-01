<template>
  <div class="home">
    <Navbar />
    <Carousel />
  </div>
</template>

<script>
import Navbar from '../components/Navbar'
import Carousel from '../components/Carousel'
export default {
  name: 'Home',
  components: { Navbar, Carousel }
}
</script>
