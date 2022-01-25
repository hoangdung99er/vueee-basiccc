<template>
  <ul>
    <resource-item
      :key="resource.id"
      v-for="resource in resources"
      :resource="resource"
    ></resource-item>
  </ul>
</template>

<script>
import ResourceItem from './ResourceItem.vue';
export default {
  components: {
    ResourceItem,
  },
  inject: ['resources'],
};
</script>

<style scoped>
ul {
  list-style: none;
  margin: 0;
  padding: 0;
  margin: auto;
  min-width: 40rem;
}
</style>
