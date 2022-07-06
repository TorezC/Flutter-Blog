<template>
  <div class="header">
    <div class="logo">
      <img src="../assets/DasdasLogo.png" />
    </div>
    <div class="header-icon-container">
      <img class="header-icon" src="../assets/twitter.png" />
      <h4>.</h4>
      <img class="header-icon" src="../assets/dribbble.png" />
      <h4>.</h4>
      <img class="header-icon" src="../assets/figma.png" />
      <h4>.</h4>
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
    height: 100px;
    display: flex;
    justify-content: space-between;
    margin:  40px 70px;
  }
  .header-icon-container{
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .header-icon, h4{
    width: 30%;
    height: 30%;
    margin-right: 20px;
  }
</style>