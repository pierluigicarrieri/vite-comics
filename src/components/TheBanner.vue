<script>
    export default {
        name: "TheBanner",    
        data() {
                return {
                    listItems: [
                        {
                            name: "DIGITAL COMICS",
                            image: "digital-comics.png"
                        },
                        {
                            name: "DC MERCHANDISE",
                            image: "merchandise.png"
                        },
                        {
                            name: "SUBSCRIPTION",
                            image: "subscriptions.png"
                        },
                        {
                            name: "COMIC SHOP LOCATOR",
                            image: "shop-locator.png"
                        },
                        {
                            name: "DC POWER VISA",
                            image: "power-visa.png"
                        }
                    ]
                }
            }
}
</script>

<template>

    <div class="banner bg-primary">
        <div class="container">
            <nav class="d-flex align-items-center">
                <ul class="nav p-5">
                    <li class="nav-item d-flex align-items-center" v-for="element in listItems">
                        <img v-bind:src="`../assets/img/buy-comics-${element.image}`" alt="">
                        <a class="nav-link" href="#">{{ element.name }}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </div>
    
</template>

<style scoped>

img {
    height: 60px;
}

a {
    color: #FFFFFF;
}

</style>