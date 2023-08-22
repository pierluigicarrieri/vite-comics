<script>
    export default {
        name: "TheBanner",    
        data() {
                return {
                    listItems: [
                        {
                            name: "DIGITAL COMICS",
                            image: "comics-digital-comics.png"
                        },
                        {
                            name: "DC MERCHANDISE",
                            image: "comics-merchandise.png"
                        },
                        {
                            name: "SUBSCRIPTION",
                            image: "comics-subscriptions.png"
                        },
                        {
                            name: "COMIC SHOP LOCATOR",
                            image: "comics-shop-locator.png"
                        },
                        {
                            name: "DC POWER VISA",
                            image: "dc-power-visa.svg"
                        }
                    ]
                }
            }
}
</script>

<template>
    <div class="banner bg-primary z-1">
        <div class="container">
            <nav class="d-flex justify-content-center align-items-center fs-6">
                <ul class="nav p-5">
                    <li class="nav-item d-flex align-items-center px-4" v-for="element in listItems">
                        <img v-bind:src="`/public/img/buy-` + element.image" alt="">
                        <a class="nav-link" href="#">{{ element.name }}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </div> 
</template>

<style scoped>
img {
    height: 50px;
}

a {
    color: #FFFFFF;
    font-size: 0.8rem;
}

li:last-child > img {
    height: 40px;
}
</style>