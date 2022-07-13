<template>
  <div>
    <Suspense>
      <template #default><Component /></template>
      <template #fallback> loading</template>
    </Suspense>
  </div>
</template>

<script setup></script>
