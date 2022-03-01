<script>
import { reactive, ref } from 'vue';

const counter = reactive({ count: 0 });
const message = ref('Hello');
</script>

<template>
  <h2>Declarative rendering</h2>
  <p>{{ message }}</p>
  <p>count: {{ counter.count }}</p>
</template>
