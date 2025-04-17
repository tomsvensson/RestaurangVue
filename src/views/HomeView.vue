<template>
  <div class="home">
    <h1>Välkommen till Restaurang Vue</h1>
    <p>Vi erbjuder utsökt mat och en fantastisk atmosfär. Kom och besök oss!</p>
  </div>
  <div class="restaurant">
    <img alt="Restaurant" src="../assets/restaurant.png" />
  </div>
</template>

<script>
export default {
  name: 'HomeView'
}
</script>

<style scoped>
.home {
  text-align: center;
}
.restaurant {
    text-align: center;
  }
  img {
    max-width: 50%;
    height: 50%;
    margin: 0 auto;

  }
</style>