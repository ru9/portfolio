<template>
  <div class="outer-container">
    <div class="background-shape">
      <div class="text-wrapper">
        <p class="bolder">
          Det kan kanskje være overveldende å tenke på hvor mye arbeid
          som skal til for å bygge et hus. På lik linje å ta del i den digitale hverdagen.
        </p>
        <p>
          Du vil selfølgelig være aktuell. Men terskelen har blitt litt for høy, og du trenger noen til
          å ta de rette besluttningene som gir resultatene du ønsker.
        </p>
        <p>Enten om du trenger en full løsning eller bare en webside, så er vi her for å hjelpe akkuratt deg.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.text-wrapper {
  position: relative;
  left: -3.5%;
  transform: rotate(3deg) scale(0.9);
  max-width: 90vw;
  padding: 2rem 1rem;
}
.text-wrapper > p {
  padding: 0.5rem 1.5rem 0.5rem 1.5rem;
  color: white;
  text-indent: 0.5rem;
  text-align: left;
}
.bolder {
  font-size: 1.5rem;
}

/* 
* --Shapes--
*/
.background-shape {
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  transform: rotate(-3deg) scale(1.1);
  background-color: #3a5d86;
  min-width: 110vw;
}
</style>