<template>
  <Menu></Menu>
  <Encoder></Encoder>
  <Footer></Footer>
</template>

<script>

import Menu from './components/Menu'
import Encoder from './components/Encorder'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Menu,
    Footer,
    Encoder
  }
}
</script>

<style>


</style>
