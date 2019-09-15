<template>
  <div class="outer-container">
    <div class="background-shape">
      <div class="text-wrapper">
        <h1>Title</h1>
        <p>
          Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
          been the industry's standard dummy text ever since the 1500s, when an unknown printer took
          a galley of type and scrambled it to make a type specimen book. It has survived not only five
          centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
          It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages,
          and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
        </p>
        <q>Something something really smart</q>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.text-wrapper {
  transform: rotate(3deg);
  color: white;
  padding: 5rem 2rem 5rem 2rem;
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
  max-width: 100%;
  background-image: none;
  display: inline-block;
}
</style>