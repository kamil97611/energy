<template>
  <header class="main--header">
      <nav class="main-nav">
          <ul class="nav-links">
              <nuxt-link to="/Onas" tag="li"><a>O nas</a></nuxt-link>
              <nuxt-link to="/Kontakt" tag="li"><a>Kontakt</a></nuxt-link>
              <nuxt-link to="/Corobimy" tag="li"><a>Co robimy</a></nuxt-link>
              <nuxt-link to="/Dlaczego" tag="li"><a>Dlczego</a></nuxt-link>
              <nuxt-link to="/Dlakogo" tag="li"><a>Dla kogo</a></nuxt-link>
              <nuxt-link to="/Cozyskujesz" tag="li"><a>Co zyskujesz</a></nuxt-link>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped>
  .main-header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background: green;
  }
</style>