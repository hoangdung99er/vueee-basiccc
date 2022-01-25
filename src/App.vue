<template>
  <the-header title="Remember me!"></the-header>
  <the-resource></the-resource>
  <!-- <stored-resources :resources="storedResources"></stored-resources> -->
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TheResource from './components/TheResource.vue';

export default {
  components: {
    TheHeader,
    TheResource,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}

html {
  font-family: 'Courier New', Courier, monospace;
}

body {
  margin: 0;
  padding: 0;
}
</style>
