<script setup lang="ts">
const { myLayer } = useAppConfig()

const test = ref<string>(1)
</script>

<template>
  <div>
    <h1>Hello World!</h1>
    <pre>{{ myLayer }}</pre>
  </div>
</template>
