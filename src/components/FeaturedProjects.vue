<template>
    <div class="project-card"> 
        <img :src="img" alt="">
        <h3>{{ title }}</h3>
        <p>{{ text }}</p>
        <div class="project-btns">
            <MainButton text="View Live"  className="var1"/>
            <MainButton text="Git Hub Repo"  className="var2"/>
        </div>
    </div>
</template>
<script setup>
import MainButton from './MainButton.vue';
    const props = defineProps({
        title: String,
        img: String,
        text: String,


})
</script>
<style>
.project-card{
background-color: #31313F;
padding: 16px;
border-radius: 8px;

}
.project-card img{
    width: 100%;
    height: 173px;
    border-radius: 8px;
    object-fit: cover;
}
.project h3{
    font-size: 24px;
    font-weight: bold;
    color: #7562e0;
}
.project-btns{
    display: flex;
    gap: 10px;
}
</style>