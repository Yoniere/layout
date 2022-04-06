<template>
  <section class="benefits-list main-layout flex">
        <ul class="list flex">
            <li class="benefits"/> <benefits-preview1 />
            <li class="benefits"/> <benefits-preview2 />
            <li class="benefits"/> <benefits-preview3 />
            <li class="benefits"/> <benefits-preview4 />
        </ul>
  </section>
</template>

<script>
import benefitsPreview1 from "./benefits-preview1.vue";
import benefitsPreview2 from "./benefits-preview2.vue";
import benefitsPreview3 from "./benefits-preview3.vue";
import benefitsPreview4 from "./benefits-preview4.vue";
export default {
  name:"benefits-list",
  components: {
benefitsPreview1,
benefitsPreview2,
benefitsPreview3,
benefitsPreview4
  }
};
</script>

<style>
</style>