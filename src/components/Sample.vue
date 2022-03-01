<template>
  <div data-cy="greeting">

    <h3>{{ testMsg }}</h3>
  </div>

</template>

<script lang="ts" setup>
import { ref } from 'vue';

const testMsg = ref('Good morning');

</script>
