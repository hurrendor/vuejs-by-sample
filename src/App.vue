<template>
    <div>
        <hello-component
        v-model="message"
    />
    </div>    
</template>

<script lang="ts">
import Vue from 'vue';
import HelloComponent from './Hello.vue';

export default ({
    name: 'App',
    extends: Vue,
    data() {
        return {
            message: 'Hello from Aspp',
        };
    },
    components: {
        HelloComponent,
    },
});
</script>