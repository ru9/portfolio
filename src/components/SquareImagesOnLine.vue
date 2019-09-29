<template>
  <div class="outer-container">
    <div>
      <img src="../assets/tst.png" alt />
    </div>
    <div>
      <img src="../assets/tst.png" alt />
    </div>
    <div>
      <img src="../assets/tst.png" alt />
    </div>
    <div>
      <img src="../assets/tst.png" alt />
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