<template>
  <footer class="mt-5">All rights reserved. {{ currentYear }}</footer>
</template>

<script>
export default {
  data() {
    return {
      currentYear: new Date().getFullYear()
    };
  }
};
</script>

<style>
</style>
