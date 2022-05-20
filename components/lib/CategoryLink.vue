<template>
  <NuxtLink :to="`/${category.slug}`">
    {{ category.name }}
  </NuxtLink>
</template>

<script>
export default {
  props: {
    category: {
      type: Object,
      required: true
    }
  }
}
</script>
