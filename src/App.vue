<template>
    <v-app>
        <h1>{{message}}</h1>
        <!-- <hello-component
        :message="message"
        :on-change="onChange"
    /> -->
    </v-app>    
</template>

<script lang="ts">
import Vue from 'vue';
// import HelloComponent from './Hello.vue';

export default Vue.extend({
    name: 'App',
    // components: {
    //     HelloComponent,
    // },
    data() {
        return {
            message: 'Hello from Aspp',
        };
    },
    // methods: {
    //     onChange(event) {
    //     this.message = event.target.value;
    //     },
    // },
});
</script>