<template>
    <div>
        <hello-component
        :message="message"
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
    methods: {
    },
    components: {
        HelloComponent,
    },
});
</script>