<template>
  <div class="outer-container">
    <div class="card">
      <img src="../assets/tst.png" alt />
      <div class="project-text">Some awesome project</div>
    </div>
    <div class="card">
      <img src="../assets/tst.png" alt />
      <div class="project-text">Some awesome project</div>
    </div>
    <div class="card">
      <img src="../assets/tst.png" alt />
      <div class="project-text">Some awesome project</div>
    </div>
    <div class="card">
      <img src="../assets/tst.png" alt />
      <div class="project-text">Some awesome project</div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.outer-container {
  display: flex;
  flex-wrap: nowrap;
  overflow-x: auto;
  margin: 4rem 0;
  padding: 1rem 1rem 2rem 1rem;
}
.card {
  display: flex;
  flex-direction: column;
  flex: 0 0 auto;
  width: 80vw;
  margin-right: 3rem;
  padding-bottom: 2rem;
  box-shadow: -3px 3px 5px 5px #ccc;
}
.card > img {
  object-fit: cover;
  width: inherit;
  height: inherit;
}
.project-text {
  font-weight: 900;
  margin: 1rem 1rem;
  text-align: left;
  font-size: 1.3rem;
}
</style>