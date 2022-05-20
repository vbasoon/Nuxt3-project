<template>
  <div>
    <h2>Category: {{ category.name }}</h2>
    <PostsList :params="{ category: category.id }" />
  </div>
</template>

<script>
export default {
  async asyncData ({ params, $axios, error }) {
    const { category: categorySlug } = params

    try {
      const resp = await $axios.$get(
        'https://news-demo.csuwebdev.cloud/api/news/categories'
      )

      const category = resp.results.find(i => i.slug === categorySlug)

      return { category }
    } catch (e) {
      error(e)
    }
  },
  head () {
    return {
      title: this.category?.name
    }
  }
}
</script>
