<template>
  <form>
    <label for="fname">Imię:</label><br>
    <input type="text" id="fname" name="fname" value=""><br>
    <label for="lname">Nazwisko:</label><br>
    <input type="text" id="lname" name="lname" value=""><br>
    <label for="email">Adres E-mail:</label><br>
    <input type="email" id="email" name="Email" value=""><br>
    <label for="phone">Numer kontaktowy:</label><br><br>
    <input type="tel" id="phone" name="phone" placeholder="123-446-789" pattern="[0-9]{3}-[0-9]{3}-[0-9]{3}" required><br><br>
    <input type="submit" value="Wyślij">
  </form> 
</template>

<script>
export default {
    
}
</script>

<style scoped>
#phone {
    text-align: center;
}
</style>