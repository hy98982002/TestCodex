<template>
  <div>
    <p>当前接口地址为：{{ apiBaseUrl }}</p>
  </div>
</template>

<script setup>
const apiBaseUrl = import.meta.env.VITE_API_BASE_URL
</script>
