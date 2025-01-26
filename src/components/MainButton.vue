<template>
    <button class="main-btn" :class="className">{{ text }}</button>
</template>
<script setup>
const props = defineProps({
    text:String,
    className:String,
}) 
</script>
<style>
.main-btn{
padding: 8px 24px;
border-radius: 8px;
border: 1ox solid #7562e0;
color: #fff;
}
.var1{
    background-color: #7562e0;
}
.var2{
    background-color: transparent;
}
</style>