<template>
  <div class="home">
    <about />
  </div>
</template>
<script>
import header from "../components/header.vue";
import about from "../components/about.vue";
export default {
  components: {
    header,
    about,
  },
};
</script>

<style>
body {
  background: #e6e6e6;
}
</style>
