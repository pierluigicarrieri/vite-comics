<script>
export default {
    props: {
        thumb: String,
        series: String
    }
}
</script>

<template>
    <div class="card h-100 border-0 text-white">
        <img :src="thumb" alt="">
        <div class="card-body bg-dark">
            {{ series }}
        </div>
    </div>
</template>

<style lang="scss" scoped>

    img {
        height: 200px;
    }

</style>