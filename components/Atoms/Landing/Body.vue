<template>
  <section class="container">
      <arcticle class="boxystyle">
          <div class="thumbnail" style="background-image: url('https://image.flaticon.com/icons/png/512/1670/1670355.png')"></div>
          <nuxt-link to="/What" class="textdeco">Co robimy?</nuxt-link>
      </arcticle>
       <arcticle class="boxystyle">
          <div class="thumbnail" style="background-image: url('https://cdn1.iconfinder.com/data/icons/dollar-5/512/hand_euro_money-512.png')"></div>
          <nuxt-link to="/Why" class="textdeco">Dlaczego?</nuxt-link>
      </arcticle>
       <arcticle class="boxystyle">
          <div class="thumbnail" style="background-image: url('https://cdn.onlinewebfonts.com/svg/img_454673.png')"></div>
          <nuxt-link to="/Whom" class="textdeco">Dla kogo?</nuxt-link>
      </arcticle>
  </section>
</template>

<script>
export default {
}
</script>

<style scoped>
.container {
display: flex;
flex-flow: row wrap;
justify-content: center;
align-items: center;
height: 100%;
width: 100%;
margin-top: 12rem;
margin-bottom: 5rem;
}
.boxystyle {
  display: flex;
box-sizing: border-box;
width: 400px;
padding: 8px;
justify-content: center;
align-items: center;
text-align: center;
box-shadow: 10px 10px 10px grey;
border-radius: 100px;
}
.thumbnail {
background-position: center;
background-size: cover;
width: 50%;
height: 200px;
border-radius: 10%;
justify-content: center;
}
.textdeco {
color: black;
text-decoration: none;
}
</style>