<template>
  <section class="container">
      <arcticle class="boxystyle">
          <div class="thumbnail" style="background-image: url('https://image.flaticon.com/icons/png/512/1670/1670355.png')"></div>
          <nuxt-link to="/Corobimy">Co robimy?</nuxt-link>
      </arcticle>
       <arcticle>
          <div class="thumbnail" style="background-image: url('https://cdn1.iconfinder.com/data/icons/dollar-5/512/hand_euro_money-512.png')"></div>
          <nuxt-link to="/Dlaczego">Dlaczego?</nuxt-link>
      </arcticle>
       <arcticle>
          <div class="thumbnail" style="background-image: url('https://cdn.onlinewebfonts.com/svg/img_454673.png')"></div>
          <nuxt-link to="/Dlakogo">Dla kogo?</nuxt-link>
      </arcticle>
  </section>
</template>

<script>
export default {
  layout: 'landing'
}
</script>

<style scoped>
.container {

}
.boxystyle {

}
.thumbnail {

}
</style>