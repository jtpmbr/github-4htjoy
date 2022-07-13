<template>
  <pre>component loaded</pre>
</template>

<script>
export default {
  async setup() {
    await new Promise((r) => setTimeout(r, 10000));
  },
};
</script>
