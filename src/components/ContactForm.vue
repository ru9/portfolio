<template>
  <div class="outer-container">
    <div>
      <h1>Spørsmål?</h1>
      <p>Spør oss gjerne om det du vil</p>
    </div>
    <form name="contact" action="/thank-you" netlify-honeypot="bot-field" method="post" netlify>
      <input type="hidden" name="form-name" value="contact" />
      <input name="bot-field" hidden />
      <div>
        <input type="text" name="firstname" placeholder="Fornavn*" />
      </div>
      <div>
        <input type="text" name="lastname" placeholder="Etternavn*" />
      </div>
      <div>
        <input type="email" name="email" placeholder="Email*" />
      </div>
      <div>
        <select type="select" name="options">
          <option value="Hvordan fant du oss?">Hvordan fant du oss?</option>
          <option value="Fra en venn">Fra en venn</option>
          <option value="Søk i google">Søk i google</option>
          <option value="Jeg er tidligere kunde">Jeg er tidligere kunde</option>
          <option value="Gjennom reklame">Gjennom reklame</option>
        </select>
      </div>
      <div>
        <textarea name="message" placeholder="Melding*"></textarea>
      </div>
      <div>
        <input class="not-italic send-button" type="submit" value="Send melding" />
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
form {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin: 0 auto;
  width: 80vw;
}
input,
textarea,
select {
  width: 100%;
  padding: 0.9rem 1rem;
  margin: 0.5rem 0;
  background-color: #3a5d86;
  font-size: 1rem;
  font-family: "Quicksand", sans-serif;
  border: none;
  color: white;
}
textarea {
  height: 7rem;
}
::placeholder {
  color: white;
  font-style: italic;
}
form > div {
  width: 80vw;
  display: flex;
  justify-content: center;
}
.not-italic {
  font-style: normal;
}
.send-button {
  background-color: #ff6f00;
  color: black;
  font-size: 1.1rem;
  font-weight: 900;
}
</style>