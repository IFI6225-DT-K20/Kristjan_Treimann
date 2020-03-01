<template lang="pug">
  div.container
    div.row
      div.v-container-fluid
        svg.logo
          include ../assets/images/lhv-logo.svg
        <router-link to="/">Pank</router-link>
        <router-link to="/finance">Finantsportaal</router-link>
        <router-link to="/investor">Investor</router-link>
</template>
<script>
export default {
  name: 'Navbar',
  data() {
    return
  }
}
</script>

<style lang="stylus" scoped>
.container {
  position: relative;
  padding-top: 20px;
  padding-bottom: 20px;
  background: #fff;
  height: 100px;
  text-transform: uppercase;
  font-size: 11px;
  line-height: 20px;
}
.v-container-fluid {
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}
.logo {
  width: 84px;
  height: 28px;
  padding-left: 0px;
  padding-right: 40px;
  line-height: 60px;
}
.left {
  float: left;
}
.row {
  margin-right: -15px
  margin-right: -15px
  border: 1px solid red
}
</style>
