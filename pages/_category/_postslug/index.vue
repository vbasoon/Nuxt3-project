<template>
  <div>
    <h2>Post page</h2>
    <h3>Title: {{ post.title }}</h3>
    <h4>Author: {{ post.author }}</h4>
    <h4>Category: <CategoryLink :category="post.category" /></h4>
    <h4>
      Tags:
      <TagLink
        v-for="tag in post.tags"
        :key="tag.id"
        :tag="tag"
      />
    </h4>
    <span>Text:</span>
    <div v-html="post.content" />

    <div style="text-align: left; display: inline-block; max-width: 500px;">
      <div v-for="(value, key) in post" :key="key" style="margin-top: 4px;">
        <b>{{ key }}:</b> <span>{{ value }}</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  async asyncData ({ params, $axios, error }) {
    const { postslug } = params

    try {
      const post = await $axios.$get(
        `https://news-demo.csuwebdev.cloud/api/news/posts/slug/${postslug}/`
      )

      return { post }
    } catch (e) {
      return error(e)
    }
  },
  head () {
    return {
      title: this.post?.title
    }
  },
}
</script>
