<template>
    <h2 class="Section_title">{{ title }}</h2>
</template>
<script setup>
    const props = defineProps({
        title:String,
    })
</script>
<style>
    .Section_title{
        font-size: 32px;
        color: #7562e0;
    }
    .services{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        gap: 20px;
        margin-top: 40px;
        
    }
</style>