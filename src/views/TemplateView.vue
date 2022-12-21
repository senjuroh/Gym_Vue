<template>
  <div>
    <!-- Navbar -->
    <navbar-comp />

    <!-- Main Section -->
    <main><slot></slot></main>

    <!-- Footer -->
    <footer-comp />
  </div>
</template>

<script>
import NavbarComp from "@/components/NavbarComp.vue";
import FooterComp from "@/components/FooterComp.vue";
export default {
  name: "TemplateView",
  components: {
    NavbarComp,
    FooterComp,
  },
};
</script>

<style lang="scss" scoped>
</style>