<template>
  <Cover />
  <Introduce />
  <Catalog />
  <TheKhuePavilion />
  <Building />
  <HWK />
  <Footer />
</template>

<script>

import Cover from './components/Cover.vue'
import Introduce from './components/Introduce.vue'
import Catalog from './components/Catalog.vue'
import TheKhuePavilion from './components/TheKhuePavilion.vue'
import Building from './components/Building.vue'
import HWK from './components/HWK.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Cover,
    Introduce,
    Catalog,
    TheKhuePavilion,
    Building,
    HWK,
    Footer
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;1,100;1,200;1,300;1,400;1,500;1,600&display=swap');

* {
  font-family: 'Poppins', sans-serif;
}
</style>
