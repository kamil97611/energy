<template>
  <section class="dlaczego">
      <article class="textowy">
          <div class="thumbnail" style="background-image: url('https://img.pngio.com/icon-contact-us-146397-free-icons-library-contact-icons-png-600_564.jpg')"></div>
          <h1>Konsorcjum „AUDYTY ENERGETYCZNE” Lider Konsorcjum: EL BARCO Sp. z o.o.</h1>
          <p1>www.audyty.info | kontakt@audyty.info <br> tel.: +48 (58) 333 46 09 <br>Siedziba: Gdynia (81-504), ul. Łowicka 63A <br> KRS: 315326  NIP: PL5862223551 <br>VIII Wydział Gospodarczy KRS Sądu Rejonowego Gdańsk-Północ</p1>
          <h2>ALEKSANDRA CIEŚLAK<br>Specjalista ds. sprzedaży<br>+48 (58) 333 46 09</h2>
          <Form />
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
    margin-bottom: 5rem;
    overflow: auto;

}
.textowy {
    box-sizing: border-box;
    width: 400px;
    padding: 8px;
    text-align: center;
}
.thumbnail {
    background-position: center;
    background-size: cover;
    width: 100%;
    height: 400px;
}
</style>