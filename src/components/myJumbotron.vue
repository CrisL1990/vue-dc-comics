<template>
  <div class="jumbo">
      <img src="../assets/img/jumbotron.jpg" alt="TeenTitans">
  </div>
</template>

<script>
export default {

    name: "myJumbotron",
}
</script>

<style scoped lang="scss">
    .jumbo{
      width: 100%;
      height: 350px;
      
      img{
        width: 100%;
        max-height: 350px;
        object-fit: cover;
        object-position: top;
      }
    }
</style>