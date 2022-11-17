<template>
  <div class="single-post-page">
    <section class="post">
      <h1 class="post-title">This is my post</h1>
      <div class="post-details">
        <div class="post-detail">Last updated on ....</div>
        <div class="post-detail">written by ....</div>
      </div>
      <p class="post-content">Content of the post</p>
    </section>
    <section class="post-feedback">
      <p>Let me know what you think abot my post, send me feedback to <a href="mailto:example@hello.com">example@hello.com</a></p>
    </section>
  </div>
</template>

<style>

.single-post-page {
  padding: 30px;
  text-align: center;
  box-sizing: border-box;
  width: 100%;
}

.post {
  width: 100%;
}

@media (min-width: 768px) {
  .post {
    width: 600px;
    margin: auto;
  }
}

.post-title {
  margin: 0;
}

.post-details {
  padding: 10px;
  box-sizing: border-box;
  border-bottom: 3px solid #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

@media (min-width: 768px) {
  .post-details {
    flex-direction: row;
  }
}

.post-detail {
  color: rgb(88, 88, 88);
  margin: 0 10px;
}

.post-feedback a {
  color: red;
  text-decoration: none;
}

.post-feedback a:hover,
.post-feedback a:active {
  color: salmon;
}</style>
