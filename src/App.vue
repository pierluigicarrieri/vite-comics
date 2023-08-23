<script>

  import TheHeader from "./components/TheHeader.vue"
  import TheBanner from "./components/TheBanner.vue"
  import TheFooter from "./components/TheFooter.vue"
  import TheCard from "./components/TheCard.vue"
  import assetList from "../assets.js"

  console.log(assetList);

  export default {
    components: {
        TheHeader,
        TheBanner,
        TheFooter,
        TheCard
    },
    data() {
      return {
        assetList
      }
    }

  }
</script>

<template>
  <div class="main-wrapper d-flex flex-column h-100">
    <TheHeader></TheHeader>
    <main class="bg-dark text-white">
      <img class="jumbo" src="./assets/jumbotron.jpg" alt="">
      <div class="container py-4">
        <div id="current-series" class="bg-primary p-2">CURRENT SERIES</div>
        <div class="row row-cols-6 g-2">
          <div class="col" v-for="(asset) in assetList">
            <TheCard 
            :thumb="asset.thumb" 
            :series="asset.series"
            ></TheCard>
          </div>
        </div>
        <div class="d-flex justify-content-center">
          <button class="btn btn-primary m-auto">LOAD MORE</button>
        </div>
        
      </div>
    </main>
    <TheBanner></TheBanner>
    <TheFooter></TheFooter>
  </div>
</template>

<style lang="scss">

  .jumbo {
    height: 400px;
    width: 100%;
  }

  #current-series {
    margin-top: -50px;
    width: fit-content;
    position: absolute;
  }

</style>
