<template>
  <div>
    <form name="contact" action="/thank-you" netlify-honeypot="bot-field" method="post" netlify>
      <input type="hidden" name="form-name" value="contact" />
      <input name="bot-field" hidden />
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
        <input type="submit" value="Send message" />
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