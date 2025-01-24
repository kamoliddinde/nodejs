<template>
<div class="card">
    <img :src="img" alt="">
    <h2>{{ title }}</h2>

</div>
</template>
<script setup>
const props = defineProps({
    title:String,
    img: String,
    title1:String,
})
</script>
<style>
.card{
    background-color: #e5e5e5;
    padding: 20px;
    color: #fff;
    padding-top:150px ;
}
.card:hover{
    background-color: #7562e0;
}

</style>