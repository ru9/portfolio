<template>
  <div class="outer-container">
    <div class="service-wrapper">
      <img src="..\assets\Seo\Website_Optimization.svg" alt />
      <div>
        <div class="title">Skreddersydd</div>
        <div
          class="text"
        >Din webside må være skreddersydd til ditt formål. Denne prosessen må tas på alvor.</div>
      </div>
    </div>
    <div class="service-wrapper">
      <img src="..\assets\Seo\Keywords_Rankings.svg" alt />
      <div>
        <div class="title">Resultatdrevet</div>
        <div
          class="text"
        >Du trenger ikke bare en webside som ser flott ut, du trenger en som gir resultater.</div>
      </div>
    </div>
    <div class="service-wrapper">
      <img src="..\assets\Seo\Social_Media_Marketing.svg" alt />
      <div>
        <div class="title">Grunnmuren</div>
        <div
          class="text"
        >Vi hjelper deg å lage en solid grunnmur som du kan bygge din digitale tilstedeværelse på.</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.outer-container {
  display: flex;
  flex-direction: column;
  margin: 4rem auto;
  width: 80vw;
}
.service-wrapper {
  display: grid;
  grid-template-columns: 20% 5% 75%;
  margin: 1rem 0;
}
.service-wrapper > img {
  grid-column: 1 / 2;
  width: 80%;
  height: 80%;
  margin: auto;
}
.service-wrapper > div {
  grid-column: 3 / 4;
}
.title {
  text-align: left;
  text-transform: uppercase;
  font-weight: 900;
}
.text {
  text-align: left;
}
</style>