<template>
  <section class="dlaczego">
      <article class="textowy">
          <div class="thumbnail" style="background-image: url('https://image.flaticon.com/icons/png/512/1670/1670355.png')"></div>
          <h1>Co to jest Audyt Energetyczny?</h1>
          <p>AUDYT ENERGETYCZNY przedsiębiorstwa
jest procedurą mającą na celu przeprowadzenie szczegółowych i potwierdzonych obliczeń dotyczących proponowanych przedsięwzięć służących poprawie efektywności energetycznej oraz dostarczenie informacji o potencjalnych oszczędnościach energii.</p>
      </article>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
.dlaczego {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: center;
    height: 100%;
    width: 100%;
    margin-top: 5rem;

}
.textowy {
    box-sizing: border-box;
    width: 400px;
    padding: 8px;
}
.thumbnail {
    background-position: center;
    background-size: cover;
    width: 100%;
    height: 400px;
}
</style>