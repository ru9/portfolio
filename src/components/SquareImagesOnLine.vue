<template>
  <div class="outer-container">
    <div>
      <img src="../assets/project_1.svg" alt />
    </div>
    <div>
      <img src="../assets/project_2.svg" alt />
    </div>
    <div>
      <img src="../assets/project_3.svg" alt />
    </div>
    <div>
      <img src="../assets/project_4.svg" alt />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.outer-container {
  display: flex;
  flex-flow: row wrap;
  margin: 4rem 0;
  overflow-y: scroll;
}
.outer-container > div {
  max-width: 50vw;
  max-height: 50vw;
}
.outer-container > div > img {
  max-width: 100%;
  max-height: 100%;
}
</style>