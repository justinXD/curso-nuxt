<template>
  <div class="home-page">
    <section class="intro">
      <h1>Top tech news</h1>
    </section>
    <section class="featured-posts">
      <nuxt-link class="post-preview" :to="'/posts/' + 1">
        <article>
          <div class="post-thumbnail" style="background-image: url('https://images.pexels.com/photos/10949676/pexels-photo-10949676.jpeg?cs=srgb&dl=pexels-matheus-oliveira-10949676.jpg&fm=jpg')"></div>
          <div class="post-content">
            <h1>Post title</h1>
            <p>Preview: </p>
          </div>
        </article>
      </nuxt-link>
      <nuxt-link class="post-preview" :to="'/posts/' + 2">
        <article>
          <div class="post-thumbnail" style="background-image: url('https://images.pexels.com/photos/735911/pexels-photo-735911.jpeg?cs=srgb&dl=pexels-soumil-kumar-735911.jpg&fm=jpg')"></div>
          <div class="post-content">
            <h1>Post title</h1>
            <p>Preview: </p>
          </div>
        </article>
      </nuxt-link>
    </section>
  </div>
</template>

<script>

</script>

<style scoped>
.intro {
  height: 300px;
  position: relative;
  padding: 30px;
  box-sizing: border-box;
  background-position: center;
  background-size: cover;
}

.intro h1 {
  position: absolute;
  top: 10%;
  left: 5%;
  width: 90%;
  font-size: 1.5rem;
  color: black;
  background-color: rgb(211, 211, 211);
  padding: 10px;
  border-radius: 10px;
  box-shadow: 3px 3px 3px black;
  box-sizing: border-box;
  border: 1px solid black;
}

@media (min-width: 768px) {
  .intro h1 {
    font-size: 2rem;
  }
}

.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

.post-preview {
  border: 1px solid #ccc;
  box-shadow: 0 2px 2px #ccc;
  background-color: white;
  width: 90%;
}

a {
  text-decoration: none;
  color: black;
}

@media (min-width: 850px) {
  .post-preview {
    width: 400px;
    margin: 10px;
  }
}

.post-thumbnail {
  width: 100%;
  height: 200px;
  background-position: center;
  background-size: cover;
}

.post-content {
  padding: 10px;
  text-align: center;
}

a:hover .post-content,
a:active .post-content {
  background-color: #ccc;
}
</style>
