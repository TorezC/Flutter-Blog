<template>
  <div>
    <BlogHeader />
    <div class="main-container">
      <div class="container">
        <div class="content-title">
          <img src="../assets/rocket.png" alt="rocket" />
          <h2>Optimizing CSS for faster page loads</h2>
        </div>
        <div class="content-details-container">
          <h5>Frontend . 1 hour</h5>
          <h2>Optimizing CSS for faster page loads</h2>
          <p class="content-details">
            Not long ago I decided to improve the loading times of my website.
            It already loads pretty fast, but I knew there was still room for
            improvement and one of them was CSS loading. I will walk you through
            the process and show you how you can improve your load times as
            well.
            <br /><br />
            To see how CSS affects the load time of a webpage we first have to
            know how the browser converts an HTML document into a functional
            webpage...
          </p>
          <div style="display: flex; justify-content: space-between">
            <p>3 mins Read</p>
            <a class="read-more-link">
              <p>Read full <i class="fas fa-long-arrow-right"></i></p>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="main-container " style="margin-top: 20px">
      <div class="posts-container">
      <BlogPost />
      <BlogPost />
      <BlogPost />
      <BlogPost />
      <BlogPost />
      <BlogPost />
      </div>
    </div>
    <div class="bottom">
    <div class="bottom-join">
      <h2>Join our Team of Writers</h2>
      <h4 style="color: #6E6E6E;">On dasdas, writers earn a living doing what they love. Getting started is easy. Just pay a one time $25 fee and everything is ready to go.</h4>
      <button>JOIN US</button>
    </div>
    </div>
  </div>
</template>

<script>
import BlogHeader from "../components/BlogHeader.vue";
import BlogPost from "../components/BlogPost.vue";

export default {
  name: "BlogList",
  components: {
    BlogHeader,
    BlogPost

  },
};
</script>

<style scoped>
.main-container {
  display: flex;
  justify-content: center;
  align-items: center;
}
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
  border: 1px solid #f5f5f5;
  border-radius: 5px;
  padding: 10px;
}
.content-title {
  background-color: #ef5623;
  color: white;
  height: 280px;
  width: 500px;
  position: relative;
}
.content-title > img {
  position: absolute;
  left: 16px;
  top: 64px;
}
.content-title > h2 {
  position: absolute;
  width: 434px;
  left: 16px;
  top: 136px;
  font-family: "Playfair Display";
  font-weight: 900;
  font-size: 36px;
}
.content-details {
  color: #6e6e6e;
  width: 600px;
}
.read-more-link {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 8px;
  color: #1473E6;
}
.posts-container{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  width: 75%;
}
.bottom{
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.bottom-join{
  width: 50%;
}
.bottom-join > h2{
  text-align: center;
  font-size: 32px;
}
.bottom-join > h4 {
  text-align: center;
  font-size: 18px;
}
.bottom-join > button{
  width: 177px;
  height: 45px;
  background-color: black;
  color: white;
}
</style>
