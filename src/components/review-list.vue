<template>
  <section class="review-list main-layout">
      <div class="review-section flex">
      <review1-preview />
      <review2-preview />
      <review3-preview />
      </div>
  </section>
</template>

<script>
import review1Preview from "./review1-preview.vue";
import review2Preview from "./review2-preview.vue";
import review3Preview from "./review3-preview.vue";
export default {
    name:"review-list",
    components: {
        review1Preview,
        review2Preview,
        review3Preview
    }
};
</script>

<style>
</style>