<template>
  <NuxtLink :to="`/${category ? category.slug : ''}?tag=${tag.slug}`">
    {{ tag.name }}
  </NuxtLink>
</template>

<script>
export default {
  props: {
    tag: {
      type: Object,
      required: true
    },
    category: {
      type: Object,
      default: null
    },
  },
}
</script>
