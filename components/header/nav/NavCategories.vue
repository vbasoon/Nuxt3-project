<template>
  <ul>
    <li>
      <NuxtLink to="/">
        Main
      </NuxtLink>
    </li>
    <li v-for="category in categories" :key="category.id">
      <CategoryLink :category="category" />
    </li>
  </ul>
</template>

<script>
export default {
  data () {
    return {
      categories: []
    }
  },
  async fetch () {
    try {
      const resp = await this.$axios.$get(
        'https://news-demo.csuwebdev.cloud/api/news/categories/'
      )

      const categories = resp.results
        .filter(i => i.navigation)
        .sort((a, b) => a.navigation_order - b.navigation_order)

      this.categories = categories
    } catch (e) {
      console.error(e)
      this.categories = []
    }
  }
}
</script>

<style lang="scss" scoped>
ul {
  width: 100%;
  display: flex;
  justify-content: space-evenly;
  padding: 1rem;
  background-color: rgb(238, 238, 238);
}
</style>
