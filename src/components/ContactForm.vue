<template>
  <form name="contact" method="post" netlify>
    <div>
      <input type="text" name="firstname" placeholder="Fornavn" />
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
    <div>
      <button type="submit">Send</button>
    </div>
  </form>
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