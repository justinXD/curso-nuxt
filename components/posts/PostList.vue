<template>
  <section class="post-list">
    <post-preview
    id="1"
    thumbnail="https://images.pexels.com/photos/10949676/pexels-photo-10949676.jpeg?cs=srgb&dl=pexels-matheus-oliveira-10949676.jpg&fm=jpg"
    title="hola mundo!!"
    previewText="my first post!"/>
    <post-preview
    id="2"
    thumbnail="https://images.pexels.com/photos/10949676/pexels-photo-10949676.jpeg?cs=srgb&dl=pexels-matheus-oliveira-10949676.jpg&fm=jpg"
    title="hola mundo!!"
    previewText="my second post!"/>
    <post-preview
    id="3"
    thumbnail="https://images.pexels.com/photos/10949676/pexels-photo-10949676.jpeg?cs=srgb&dl=pexels-matheus-oliveira-10949676.jpg&fm=jpg"
    title="hola mundo!!"
    previewText="my third post!"/>
  </section>
</template>

<script>
import PostPreview from '@/components/posts/PostPreview'

export default {
  components: {
    PostPreview
  }
}
</script>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
