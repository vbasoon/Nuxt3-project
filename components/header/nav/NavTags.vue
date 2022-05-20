<template>
  <ul>
    <li v-for="tag in tags" :key="tag.id">
      <TagLink :tag="tag" />
    </li>
  </ul>
</template>

<script>
export default {
  data () {
    return {
      tags: []
    }
  },
  async fetch () {
    try {
      const resp = await this.$axios.$get(
        'https://news-demo.csuwebdev.cloud/api/news/tags/'
      )

      this.tags = resp.results
    } catch (e) {
      console.error(e)
      this.tags = []
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
  background-color: rgb(245, 245, 245);
  font-size: 0.8rem;
}
</style>
