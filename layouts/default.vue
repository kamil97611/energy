<template>
  <div>
    <TheHeader />
    <main class="main-content">
    <Nuxt />
    </main>
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader'

export default {
  components: {
    TheHeader
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
}
.main-content {
  margin-top: 4rem;
  background-color:lightgray;
}
</style>