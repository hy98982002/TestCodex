<template>
  <nav class="nav-bar">
    <RouterLink to="/">首页</RouterLink>
    <RouterLink to="/about">关于我们</RouterLink>
  </nav>
</template>

<script lang="ts" setup>
</script>

<style scoped>
.nav-bar {
  display: flex;
  gap: 1rem;
  background-color: #f5f5f5;
  padding: 1rem;
}
</style>
