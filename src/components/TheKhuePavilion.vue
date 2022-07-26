<template>
    <section class="hero has-background-light">
        <div class="hero-body">
            <div class="container">
                <div class="columns">
                    <div class="column is-6">
                        <div class="block has-text-right">
                            <span class="title-large"><b>The Khue Pavillon</b></span>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minima totam deserunt assumenda
                                voluptas numquam, obcaecati distinctio accusantium dolores blanditiis. Debitis, corrupti
                                officiis. Inventore nam repellat aut recusandae quidem voluptatem doloremque!</p>
                        </div>
                    </div>
                    <div class="column is-6">
                        <figure class="image">
                            <img :src="image1">
                        </figure>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="hero">
        <div class="hero-body">
            <div class="container">
                <div class="columns">
                    <div class="column is-6">
                        <figure class="image">
                            <img :src="image2">
                        </figure>
                    </div>
                    <div class="column is-6">
                        <figure class="image">
                            <img :src="image3">
                        </figure>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="hero">
        <div class="hero-body">
            <div class="container">
                <div class="block has-text-centered">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint
                    asperiores cupiditate soluta. Culpa, praesentium! Tempora iure sunt quis fugit. Vero error soluta
                    recusandae dolorum enim tempora accusamus quidem veritatis laboriosam.</div>
                <figure class="image">
                    <img :src="image4">
                </figure>
            </div>
        </div>
    </section>
    <section class="hero has-background-light">
        <div class="hero-body">
            <div class="container">
                <div class="tile is-ancestor">
                    <div class="tile is-5 is-parent is-vertical">
                        <div class="tile is-child">
                            <figure class="image">
                                <img :src="image6">
                            </figure>
                        </div>
                        <div class="tile is-child">
                            <figure class="image">
                                <img :src="image7">
                            </figure>
                        </div>
                    </div>
                    <div class="tile is-7 is-parent is-vertical">
                        <div class="tile is-child">
                            <figure class="image">
                                <img :src="image5">
                            </figure>
                        </div>
                        <div class="tile is-child">
                            <figure class="image">
                                <img :src="image8">
                            </figure>
                        </div>
                    </div>
                </div>
                <p class="has-text-right">Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam omnis
                    asperiores excepturi architecto. Rerum aliquam ut iure quaerat natus cumque veritatis repudiandae
                    facere asperiores illo. Enim facere dicta quisquam nemo.</p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "TheKhuePavillon",
    data() {
        return {
            image1: require('../assets/TheKhuePavilion_04.jpg'),
            image2: require('../assets/TheKhuePavilion_02.jpg'),
            image3: require('../assets/TheKhuePavilion_03.jpg'),
            image4: require('../assets/TheKhuePavilion_01.png'),
            image5: require('../assets/TheKhuePavilion_05.jpg'),
            image6: require('../assets/TheKhuePavilion_06.jpg'),
            image7: require('../assets/TheKhuePavilion_07.jpg'),
            image8: require('../assets/TheKhuePavilion_08.jpg')
        }
    }
}
</script>

<style scoped>
.title-large {
    font-size: 5rem;
}
</style>