<script>
    export default {    
        data() {
                return {
                    listitems: ["CHARACTERS", "COMICS", "MOVIES", "TV", "GAMES", "COLLECTIBLES", "VIDEOS", "FANS", "NEWS", "SHOP"],                 
                }
            }
}
</script>

<template>
    <div class="container">
        <header class="bg-warning d-flex justify-content-between">
            <img class="my-3" src="../assets/img/dc-logo.png" alt="dc-logo">
            <nav class="d-flex align-items-center">
                <ul class="nav">
                    <li class="nav-item" v-for="element in listitems">
                        <a class="nav-link" href="#"><strong>{{element}}</strong></a>
                    </li>
                </ul>
            </nav>
        </header>
    </div>
</template>

<style scoped>

img {
    aspect-ratio: 1/1;
    height: 80px;
}

a {
    color: #000000;
    font-size: 0.7rem;
}

</style>
