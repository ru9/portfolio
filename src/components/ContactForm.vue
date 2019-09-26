<template>
  <div class="outer-container">
    <form name="contact" method="POST" data-netlify="true">
      <div>
        <input type="text" name="name" placeholder="Fornavn" />
      </div>
      <div>
        <input type="text" name="lastname" placeholder="Etternavn" />
      </div>
      <div>
        <input type="email" name="email" placeholder="Email" />
      </div>
      <div>
        <textarea name="message" placeholder="Melding"></textarea>
      </div>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.outer-container {
  margin: 4rem 0;
}
input,
textarea {
  padding: 1rem;
  background-color: #ff6f002f;
  font-size: 1rem;
  color: black;
  border: none;
}
</style>