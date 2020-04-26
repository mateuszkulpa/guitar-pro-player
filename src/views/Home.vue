<template>
  <div>
    <h1>{{ counter }}</h1>
    <button @click="counter++">increment</button>
  </div>
</template>

<script>
import { ref } from "vue";
export default {
  setup() {
    const counter = ref(0);
    return { counter };
  }
};
</script>
