<template>
    <div class="post-container">
      <img src="" alt="" />
      <div class="img-post"></div>
      <p>Front-end . 1 hour</p>
      <h2>Css Grid</h2>
      <p>
        The CSS Grid Layout Module offers a grid-based layout system, with rows
        and columns, making it easier to design web pages without having to use
        floats and positioning.
      </p>
      <div style="display: flex; justify-content: space-between">
        <p>12 Min Read</p>
        <p style="color: #1473E6;">Read full <i class="fas fa-long-arrow-right"></i></p>
      </div>
    </div>
  
</template>

<script>
export default {
  name: "BlogPost",
};
</script>

<style scoped>
    /* .main-post-container{
        display: flex;
        justify-content: center;
        align-items: center;
    } */
    .post-container {
        width: 300px;
        border: 1px solid #f5f5f5;
        border-radius: 5px;
        gap: 5px;
        padding: 10px;
        margin: 20px;
    }
    .img-post{
        background-color: #FFF4E7;
        width: 100%;
        height: 200px;
    }
</style>
