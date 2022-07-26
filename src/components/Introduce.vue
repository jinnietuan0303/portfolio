<template>
    <section class="hero">
        <div class="hero-body">
            <div class="container">
                <div class="columns">
                    <div class="column is-8">
                        <h1 class="title">
                            Hello
                        </h1>
                        <div class="block">
                            <figure class="image block avatar">
                                <img :src="avatar">
                            </figure>
                        </div>
                        <div class="block">
                            <div class="columns">
                                <div class="column is-8">
                                    <h2 class="subtitle">
                                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Soluta laudantium, ex,
                                        corporis fugit
                                        aliquam officiis rerum dolores placeat in velit vitae quae quo necessitatibus.
                                        Impedit
                                        consequuntur
                                        repellendus nesciunt blanditiis consequatur.
                                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit architecto
                                        adipisci quia
                                        asperiores eveniet quis eos, doloribus voluptas rem quos porro dignissimos
                                        aliquam iure
                                        omnis, quam, veniam ex facilis debitis?
                                    </h2>
                                </div>
                                <div class="column is-4">
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="column is-4">
                        <div class="block has-text-right">
                            <h2><b>Contact</b></h2>
                            <span>Email: thisisemail@email.com</span><br>
                            <span>Phone: 0123456789</span><br>
                            <span>Instagram: @igaccount</span><br>
                            <span>Behance: @behanceaccount</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Introduce",
    data() {
        return {
            avatar: require('../assets/phwnthaoo.jpg')
        }
    }
}
</script>

<style scoped>
.avatar {
    height: auto;
    width: 30%;
}
</style>