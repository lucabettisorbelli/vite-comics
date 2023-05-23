<script>
export default {
  name: "AppHeader",

  data() {
    return {
      voci: [
        'Characters',
        'Comics',
        'Moves',
        'Tv',
        'Games',
        'Collectibles',
        'Videos',
        'Fans',
        'News',
        'Shop',
      ]
    }
  }
}
</script>

<template>
  <header>
    <div class="containerHeader d-flex justify-space-between p-1 align-items-center">
      <div class="boxLogo">
        <img src="/dc-logo.png" alt="">
      </div>
      <div class="navBar d-flex">
        <div v-for="voce in voci" class="navSection">
          <p>{{ voce }}</p>
        </div>
      </div>
    </div>
    <div class="containerImg">
      <img src="/jumbotron.jpg" alt="">
    </div>
  </header>
</template>

<style scoped>
.containerHeader {
  max-width: 1200px;
  margin: 0 auto;
}

.navSection {
  padding: 0.6rem;
}

.navSection>p {
  font-size: 1rem;
}

.containerImg {
  height: 1000px;
}

.containerImg img {
  height: 100%;
  width: 100%;
}
</style>

