<template>
  <section class="hero has-background-light">
    <div class="hero-body">
      <div class="container">
        <div class="columns">
          <div class="column is-8">
            <figure class="image">
                            <img :src="image2">
                        </figure>
          </div>
          <div class="column is-4">
            <p class="has-text-left title-large"><b>HWK Showroom</b></p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta eveniet aut corporis accusamus blanditiis corrupti dolorum aspernatur perferendis optio atque alias dicta magni impedit fuga temporibus vitae, qui unde officia.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <body>
    <section class="section">
      <div class="container">
        <figure class="image">
                            <img :src="image1" class="sketch">
                        </figure>
      </div>
    </section>
  </body>
</template>

<script>
export default {
    name: "HWK",
    data() {
        return {
            image1: require('../assets/HWK_01.jpg'),
            image2: require('../assets/HWK_02.jpg'),
        }
    }
}
</script>

<style scoped>
.title-large {
    font-size: 5rem;
}

.sketch {
    width: 70%;
    height: auto;
    margin: 0 auto;
}
</style>