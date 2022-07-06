<template>
  <div class="header">
    <div class="logo">
      <img src="../assets/DasdasLogo.png" />
    </div>
    <div class="header-icon-container">
      <img class="header-icon" src="../assets/twitter.png" />
      <img class="header-icon" src="../assets/dribbble.png" />
      <img class="header-icon" src="../assets/figma.png" />
      <img class="header-icon" src="../assets/github.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'BlogHeader'
}
</script>

<style scoped>
  .logo > img{
    width: 100px;
    height: 100px;
  }
  .header{
    height: 40px;
    display: flex;
    justify-content: space-between;
    margin:  40px 70px;
  }
  .header-icon-container{
    display: flex;
  }
  .header-icon{
    width: 80%;
    height: 80%;
    margin-right: 20px;
  }
</style>