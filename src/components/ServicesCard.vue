<template>
    <div class="services-card" :class="variant">
        <img :src="img" alt="">
        <h3>{{ title }}</h3>
        <p>{{ text }}</p>

    </div>
</template>
<script setup>
const props = defineProps({
    title:String,
    text:String,
    img:String,
    variant:String,

})
</script>
<style>
.services-card{
text-align: center;
padding: 20px;
border-radius: 10px;
}
.services-card.var1{
    border: 2px solid #7562e0;
}
.services-card.var2{
    border: 2px solid #fff;
}
.services-card.var2 h3{
    color: #7562e0;
}
</style>