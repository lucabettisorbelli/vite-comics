<script>
export default {
  name: "AppHeader",

  data() {
    return {
      voci: [
        'ciao',
        'ciaone',
        'ciaone',
        'ciaone',
        'ciaone',
        'ciaone',
        'ciaone',
        'ciaone',
        'ciaone',
        'ciaone',
      ]
    }
  }
}
</script>

<template>
  <header>
    <div class="containerHeader d-flex justify-space-between p-1 align-items-center">
      <div class="boxLogo">
        <img src="../assets/dc-logo.png" alt="">
      </div>
      <div class="navBar d-flex">
        <div v-for="voce in voci" class="navSection">
          <p>{{ voce }}</p>
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>
header {
  background-color: bisque;
  height: 15vh;
}

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
</style>

