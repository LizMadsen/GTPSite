<template>
  <div class="row m-0">
    <div class="col-1">ART PAGE, AW YEAH</div>
  </div>
</template>

<script>
export default {
  name: 'Artworks'
}
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;
  .home-card {
    width: 50vw;
    > img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
