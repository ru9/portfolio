<template>
  <div class="outer-container">
    <div class="square-shape fade-in"></div>
    <div class="square-shape2 fade-in"></div>
    <div class="portrait-wrapper fade-in">
      <img alt="startimage" src="../assets/me_white_backround.png" class="start-image" />
    </div>
    <div class="opening-text-wrapper fade-in-left">
      <h1 class="opening-text">Digital</h1>
      <h1 class="opening-text">problemløsning</h1>
      <h1 class="opening-text">
        skal være
        <a>enkelt.</a>
      </h1>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scope>
.outer-container {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  max-width: 100vw;
}
.portrait-wrapper {
  display: flex;
  justify-content: flex-end;
  width: 100vw;
  height: 100vh;
  align-items: flex-end;
  z-index: -1;
}
.start-image {
  display: flex;
  justify-content: right;
  align-items: right;
  object-fit: cover;
  height: 60vh;
  pointer-events: none;
}
.opening-text-wrapper {
  position: absolute;
  top: 15vh;
  left: 1rem;
}
.opening-text {
  font-size: 7.5vmin;
  padding: 0.5rem;
  text-align: left;
}
.opening-text > a {
  color: #ff6f00;
}

/* 
* --Shapes--
*/
.square-shape {
  position: absolute;
  height: 40vh;
  width: 40vh;
  transform: rotate(30deg);
  border-radius: 10%;
  background-color: #003459;
  top: -15vh;
  right: -15vh;
  background-image: none;
  display: inline-block;
  overflow: hidden;
}
.square-shape2 {
  position: absolute;
  height: 30vh;
  width: 30vh;
  transform: rotate(70deg);
  border-radius: 10%;
  background-color: #3a5d86;
  top: 10vh;
  right: -20vh;
  opacity: 0.95;
  background-image: none;
  display: inline-block;
  overflow: hidden;
}

/*
* --Media--
*/
@media (min-width: 768px) {
}

/* 
* --Animation--
*/
.fade-in-left {
  -webkit-animation: fade-in-left 1s cubic-bezier(0.39, 0.575, 0.565, 1) 300ms
    both;
  animation: fade-in-left 1s cubic-bezier(0.39, 0.575, 0.565, 1) 300ms both;
}
@keyframes fade-in-left {
  0% {
    transform: translateX(-50px);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}

.fade-in {
  animation: fade-in 1s cubic-bezier(0.39, 0.575, 0.565, 1) 100ms both;
}
@keyframes fade-in {
  0% {
    opacity: 0;
  }
  100% {
    opacity: default;
  }
}
</style>
