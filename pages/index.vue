<template>
  <div class="color">
    <TheHeader />
    <main class="main-content">

    </main>
    <TheFooter />
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader'
import TheFooter from '@/components/TheFooter'

export default {
  components: {
    TheHeader,
    TheFooter
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