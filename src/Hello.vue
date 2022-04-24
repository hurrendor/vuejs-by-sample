<template>
  <input v-model="message" />
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'HelloComponent',
  props: {
    message: String,
  },
});
</script>