<template>
    <section class="hero is-fullheight has-bg-img">
        <div class="hero-body is-justify-content-end">
            <div class="box">
              <article class="media">
                <div class="media-content">
                  <div class="content">
                    <p class="has-text-right">
                      <span class="title-large"><b><i>PORTFOLIO</i></b></span>
                      <br>
                      <span class="title-medium">Nguyen Phuong Thao</span>
                      <br>
                      <span class="title-small"><i>Architecture</i></span>
                    </p>
                  </div>
                </div>
              </article>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Cover"
}
</script>

<style scoped>
.has-bg-img {
    background: url('../assets/cover.jpg')center center;
    background-size: cover;
}

.title-large {
    font-size: 8rem;
}

.title-medium {
    font-size: 3rem;
}

.title-small {
    font-size: 2rem;
}
</style>