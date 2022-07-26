<template>
    <section class="hero">
        <div class="hero-body">
            <div class="container">
                <div class="columns">
                    <div class="column is-9">
                        <figure class="image">
                            <img :src="image13">
                        </figure>
                    </div>
                    <div class="column is-3">
                        <div class="tile is-parent is-vertical">
                            <div class="tile is-child">
                                <p class="has-text-left title-large"><b>Building</b></p>
                                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cumque,
                                omnis odio, delectus, ut recusandae voluptate veritatis ipsa vel hic sunt temporibus
                                commodi dolores amet rerum. Blanditiis fugit ad in tempore?</div>
                            <div class="tile is-child">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cumque,
                                omnis odio, delectus, ut recusandae voluptate veritatis ipsa vel hic sunt temporibus
                                commodi dolores amet rerum. Blanditiis fugit ad in tempore?</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="hero">
        <div class="hero-body">
            <div class="container">
                <div class="columns is-multiline">
                    <div class="column is-7">
                        <figure class="image">
                            <img :src="image11">
                        </figure>
                    </div>
                    <div class="column is-5">
                        <figure class="image">
                            <img :src="image12">
                        </figure>
                    </div>
                    <div class="column is-5">
                        <figure class="image">
                            <img :src="image9">
                        </figure>
                    </div>
                    <div class="column">
                        <figure class="image">
                            <img :src="image10">
                        </figure>
                    </div>
                </div>
                <p class="has-text-justify">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores beatae
                    delectus voluptatem ex perferendis odio quos magni, deserunt harum aut sapiente. Officia inventore
                    id dolor, accusamus atque minima cumque alias!</p>
            </div>
        </div>
    </section>
    <section class="hero has-background-light">
        <div class="hero-body">
            <div class="container">
                <div class="columns is-multiline">
                    <div class="column is-7">
                        <figure class="image">
                            <img :src="image8">
                        </figure>
                    </div>
                    <div class="column is-5">
                        <figure class="image block">
                            <img :src="image7">
                        </figure>
                        <p class="has-text-right">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloremque,
                            libero nam eligendi quaerat itaque beatae illo, repudiandae minus corporis earum vitae harum
                            eum ducimus modi explicabo suscipit, culpa eius sapiente!</p>
                    </div>
                    <div class="column is-5">
                        <figure class="image block">
                            <img :src="image6">
                        </figure>
                        <p class="has-text-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloremque,
                            libero nam eligendi quaerat itaque beatae illo, repudiandae minus corporis earum vitae harum
                            eum ducimus modi explicabo suscipit, culpa eius sapiente!</p>
                    </div>
                    <div class="column">
                        <figure class="image">
                            <img :src="image5">
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
                            <img :src="image4">
                        </figure>
                    </div>
                    <div class="column is-6">
                        <figure class="image">
                            <img :src="image3">
                        </figure>
                    </div>
                </div>
                <div class="columns">
                    <div class="column is-6">
                        <figure class="image">
                            <img :src="image2">
                        </figure>
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
</template>

<script>
export default {
    name: "Building",
    data() {
        return {
            image1: require('../assets/1.jpg'),
            image2: require('../assets/2.jpg'),
            image3: require('../assets/3.jpg'),
            image4: require('../assets/4.jpg'),
            image5: require('../assets/5.jpg'),
            image6: require('../assets/6.jpg'),
            image7: require('../assets/7.jpg'),
            image8: require('../assets/8.jpg'),
            image9: require('../assets/9.jpg'),
            image10: require('../assets/10.jpg'),
            image11: require('../assets/11.jpg'),
            image12: require('../assets/12.jpg'),
            image13: require('../assets/13.jpg')
        }
    }
}
</script>

<style scoped>
.title-large {
    font-size: 5rem;
}
</style>