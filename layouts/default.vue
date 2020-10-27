<template>
  <div>
    <div class="content">
      <Nuxt />
    </div>
    <footer>Footer</footer>
  </div>
</template>

<script>
import AppMenu from "@/components/AppMenu.vue";
export default {
  components: {
    AppMenu,
  },
};
</script>
