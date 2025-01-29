<template>
     <header  >
    <div class="container" >
      <div class="flex">
        <router-link to="/"><img src="@/assets/images/logo.png"></router-link>
        <ul class="list-itams ">
          <li><router-link to="/" active-class="active-link">Home</router-link></li>
          <li><router-link to="/about" active-class="active-link">About me</router-link></li>
          <li><router-link to="/project" active-class="active-link">Projects</router-link></li>
          <li><router-link to="/contact"  active-class="active-link">Contact</router-link></li>
        </ul>
      </div>
    </div>
  </header>  
</template>
<style>
header .active-link {
    color: #7562e0 !important;
}
</style>