<script>

  import TheHeader from "./components/TheHeader.vue"
  import TheBanner from "./components/TheBanner.vue"
  import TheFooter from "./components/TheFooter.vue"

  export default {
    
    components: {
        
        TheHeader,
        TheBanner,
        TheFooter
    }

  }
</script>

<template>
  <TheHeader></TheHeader>
  <main class="bg-dark text-white">
    <div class="container py-5 fs-4"> -- > Content goes here --</div>
  </main>
  <TheBanner></TheBanner>
  <TheFooter></TheFooter>
</template>

<style>

</style>
