<template>
  <div>
    <div class="container">
      <h1>Welcome to Restaurantly</h1>
      <NuxtLink to="restaurants" class="link"
        >Go to restaurants <span>&#10140;</span></NuxtLink
      >
    </div>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: "Restaurantly - Welcome",
});
</script>

<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;
}
.link {
  text-decoration: none;
  font-size: 1.5rem;
}
</style>
