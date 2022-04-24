<template>
    <h1>{{ message }}</h1>
</template>

<script lang="ts">
import Vue from 'vue';

export default ({
    name: 'App',
    extends: Vue,
    data() {
        return {
            message: 'Hello from Aspp',
        };
    },
});
</script>