<template>
  <n-input v-model:value="inputValue"></n-input>
</template>

<script setup lang="ts">
import { NInput } from 'naive-ui';
import { ref } from "vue";

const inputValue = ref<string>('Hello World');

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
