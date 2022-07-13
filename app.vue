<template>
  <div>
    <Loading loaded="loaded" />
    <Suspense @resolved="loaded = true">
      <Component />
      <template #fallback> <div class="text-red-700">loading</div> </template>
    </Suspense>
  </div>
</template>

<script setup>
const loaded = ref(false);
</script>
