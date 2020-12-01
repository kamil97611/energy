<template>
  <div>
    <TheHeader />
    <main class="main-content">
      <Nuxt />
    </main>
    <TheFooter />
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader.vue';
import TheFooter from '@/components/TheFooter.vue';

export default {
components: {
    TheHeader,
    TheFooter
    }
};
</script>

<style>
* {
  box-sizing: border-box;
}
body {
  font-family: "Lato", sans-serif;
}
.main-content {
  margin-top: 4,5rem;
}