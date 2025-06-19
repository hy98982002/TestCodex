
<script setup lang="ts">
import { useRouter, RouterView } from 'vue-router';

const router = useRouter();
router.replace('/');
</script>

<template>
  <RouterView />
</template>

