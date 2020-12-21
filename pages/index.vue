<template>
  <div class="color">
    <Header />
    <main class="main-content">
      <Body />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Atoms/Header'
import Footer from '@/components/Atoms/Footer'

export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style>
* {
  box-sizing: border-box;
}
body {
  font-family: "Lato", sans-serif;
  margin: 0;
  padding: 0;
  background-color: lightgray;
}
</style>