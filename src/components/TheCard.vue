<template>
<div class="card " :class="className">
    <img :src="img" alt="">
    <h2>{{ title }}</h2>


</div>
</template>
<script setup>
const props = defineProps({
    title:String,
    img: String,
    title1:String,
    className:String,
})
</script>
<style>
.card{
    background-color: rgb(167, 167, 167);
    padding:0 20px;
    color: #fff;
    padding-top:150px ;
}
.card:hover{
    background-color: #7562e0;
}
.card h2{
    font-size: 30px;
    max-width: 80%;
}
.card.active{
    background-color: #7562e0;
}

</style>