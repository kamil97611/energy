<template>
  <header class="main-header">
      <nav class="main-nav">
          <ul class="nav-links">
              <nuxt-link to="/" tag="li" class="nav-link"><a>Home</a></nuxt-link>
              <nuxt-link to="/About" tag="li" class="nav-link"><a>O nas</a></nuxt-link>
              <nuxt-link to="/Contact" tag="li" class="nav-link"><a>Kontakt</a></nuxt-link>
              <nuxt-link to="/What" tag="li" class="nav-link"><a>Co robimy</a></nuxt-link>
              <nuxt-link to="/Why" tag="li" class="nav-link"><a>Dlaczego</a></nuxt-link>
              <nuxt-link to="/Whom" tag="li" class="nav-link"><a>Dla kogo</a></nuxt-link>
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
      background:black;
      height: 4.5rem;
  }
  .main-nav {
    height: 100%;
  }
  .nav-links {
    list-style: none;
    display: flex;
    justify-content: center;
    margin: 0;
    padding: 0;
    align-items: center;
    height: 100%;
  }
  .nav-link {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 1rem;
    padding: 0.3rem;
  }
  .nav-link.nuxt-link-exact-active {
    border-bottom: 3px solid whitesmoke;
  }
  .nav-link a {
    color: white;
    display: block;
    text-decoration: none;
  }
  .nav-link a:hover,
  .nav-link a:active,
  .nav-link.nuxt-link-axact-active a {
    color: grey;
  }
</style>