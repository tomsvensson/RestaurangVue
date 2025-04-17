<template>
    <div class="contact">
      <p><strong>Telefon:</strong> 012-345 6789</p>
      <p><strong>E-post:</strong> info@restaurang.se</p>
      <p><strong>Adress:</strong> Restauranggatan 1, 12345 Staden</p>
      
      <!-- Embedded Google Map -->
      <div class="map">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3151.835434509374!2d144.9537353153169!3d-37.81627974202198!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad642af0f11fd81%3A0xf577d8c3c6b5b3b1!2sRestauranggatan%201%2C%2012345%20Staden!5e0!3m2!1sen!2sse!4v1610000000000!5m2!1sen!2sse"
          width="600"
          height="450"
          style="border:0;"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade">
        </iframe>
      </div>
    </div>
</template>

<script>
export default {
  name: 'ContactView'
}
</script>

<style scoped>
.contact {
  text-align: center;
}

.map {
  margin-top: 20px;
  display: flex;
  justify-content: center;
}
</style>