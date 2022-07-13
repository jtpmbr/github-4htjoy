<template>
  <pre>{{ test }}</pre>
</template>

<script>
export default {
  async setup() {
    const test = ref('nono');
    await new Promise((r) => setTimeout(r, 5000));
    return { test };
  },
};
</script>
