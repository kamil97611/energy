<template>
  <main class="Lang">
    <h1>{{ $t('greeting') }}</h1>

    <nuxt-link class="eng"
      v-if="$i18n.locale !== 'en'"
      :to="switchLocalePath('en')"
    >
      English
    </nuxt-link>

    <nuxt-link class="esp"
      v-if="$i18n.locale !== 'es'"
      :to="switchLocalePath('es')"
    >
      Español
    </nuxt-link>
  </main>
</template>

<style lang="scss" scoped>
.Lang {
  color:white;
  text-align: center;
  margin: 0;
  padding: 0;
  font-size: 10px;
  border: solid white 1px;
  width: 4rem;
  height: auto;
}
.esp {
  color: white;
}
.eng {
  color:white;
}
</style>