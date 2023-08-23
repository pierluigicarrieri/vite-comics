<script>
export default {
    props: {
        thumb: String,
        series: String
    }
}
</script>

<template>
    <div class="card h-100">
        <img :src="assets.thumb" alt="">
        <div class="card-body">
            {{ series }}
        </div>
    </div>
</template>

<style lang="scss" scoped>
</style>