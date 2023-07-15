<template>
  <Exercise />
  <p>{{ text }}</p>
</template>
<script setup>
  import Exercise from "./components/Exercise1-01.vue"
  const text = 'This is sample constant text'
</script>
<!-- <script>
import Exercise from "./components/Exercise1-01.vue";
export default {
  components: {
    Exercise,
  },
  data() {
    return {
      text: "Hello from Data",
    };
  },
}; -->
<!-- </script> -->
<style>
</style>