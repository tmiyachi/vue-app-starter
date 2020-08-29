<template>
  <p>{{ greeting }} World</p>
</template>

<script>
  export default {
    data() {
      return {
        greeting: 'Hello',
      };
    },
  };
</script>

<style>
  p {
    font-size: 16px;
    font-weight: bold;
    color: black;
    text-align: center;
  }
</style>
