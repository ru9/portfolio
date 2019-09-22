<template>
  <div class="outer-container">
    <div>Besøk oss på sosiale medier:</div>
    <div class="social-icon-row">
      <a href="www.facebook.com">
        <img src="../assets/social/facebook-icon.svg" alt />
      </a>
      <a href="www.twitter.com">
        <img src="../assets/social/twitter-icon.svg" alt />
      </a>
      <a href="www.linkedin.com">
        <img src="../assets/social/linkedin-icon.svg" alt />
      </a>
      <a href="www.instagram.com">
        <img src="../assets/social/instagram-icon.svg" alt />
      </a>
    </div>
    <div class="copywrite">©Abilia Digital. All Rights Reserved.</div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.outer-container {
  padding: 2rem 0;
  background-color: rgb(27, 27, 27);
  color: white;
}
.social-icon-row {
  display: flex;
  justify-content: center;
  align-content: center;
  margin-bottom: 1rem;
}
.social-icon-row > a > img {
  margin: 10px 10px;
  width: 3rem;
  height: 3rem;
}
.copywrite {
  font-size: 0.7rem;
  margin-top: 2rem;
}
</style>