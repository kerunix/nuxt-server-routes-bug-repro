<script lang="ts" setup>
// Swap the commented line to trigger the bug on and off
// const { data } = useAsyncData('count', () => $fetch('/api/helloWorld'))
const { data } = useAsyncData('count', () => $fetch('/api/hello-world'))
</script>


<template>
  <div>
    {{ data }}
  </div>
</template>
