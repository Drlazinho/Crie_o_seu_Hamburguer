<template>
  <div id="main-banner">
    <h1>Make Your Burge</h1>
  </div>
</template>

<script>
export default {
  name: "Banner"
}
</script>

<style scoped>

  #main-banner{
    background-image: url('/img/burger-home.jpg');
    background-position: 0;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #main-banner h1{
    color: white;
    text-align: center;
    font-size: 60px;
    padding: 20px 40px;
  }
</style>