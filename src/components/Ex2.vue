<script setup>
    import { ref } from 'vue'

    // Add code here
    const me = ref('/assets/me.png')
    const height = ref('200')
    const width = ref('200')

    // const image = ref({
    //     src: '/assets/me.png',
    //     width: '200',
    //     height: '200'
    // }) 

    
</script>

<template>

    <!-- Add code here -->
    <!-- <img v-bind="image" /> -->
    <img v-bind:src="me" :width="width" :height="height"/>
   
</template>
