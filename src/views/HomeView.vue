<template >
  <header  >
    <div class="container" >
      <div class="flex">
        <a href=""><img src="@/assets/images/logo.png" alt=""></a>
        <ul class="list-itams ">
          <li><a href="">Home</a></li>
          <li><a href="">About me</a></li>
          <li><a href="">Project</a></li>
          <li><a href="">Contact</a></li>
        </ul>
      </div>
    </div>
  </header>      
  <aside>
   <div class="container">
    <div class="flex ">
      <div class="main-text">
        <h3>Hello, I'm</h3>
        <h1>Jayjay D. Dinero</h1>
        <p>Freelance UI designer, Fullstack developer, & Data Miner. I create seamless web experiences for end-users.</p>
       <div class="flex-btn">
        <button class="btn-1">About me</button>
        <button class="btn-2">Project</button>
       </div>
      </div>
      <div class="main-img">
        <img src="@/assets/images/img-1.png" alt="">
      </div>

    </div>
   </div>
  </aside>
  <div class="black-line"></div>
  <section>
    <div class="container">
      <h1 class="text-1">About me:</h1>
      <p class="text-2">Hi, my name is Jayjay Dinero Dinero, i am a Fullstack web developer, UI designer, and Mobile developer. I jhave honed my skills in Web Development and advance i have core understanding of advance UI design principles. 
        Here are the major skiills i have. </p>
      <div class="section-text">
       
        <img src="@/assets/images/5+.png" alt="">
        <p>Years of experience. Specialised in building apps, while ensuring a seamless
          web experience for end users.</p>
      </div>
      <div class="cards flex">
        <div class="card-1"></div>
        <div class="card-2"></div>
        <div class="card-3"></div>
        <div class="card-4"></div>
      </div>
             
    </div>
  </section>
</template>
<script></script>
<style>

header{
  background-color: #181818;
}
.flex{
  display: flex;
  justify-content: space-between;
}
.container {
  width: 80%; 
  margin: 0 auto;
  padding: 20px;
}
.list-itams{
  display: flex;
  gap: 15px;
  font-size:20px ;
  list-style: none;
 
}
.list-itams li a{
  text-decoration: none;
  color: #fff
}
.flex-btn{
display: flex;
gap: 15px;
}
.main-text h3{
  font-size: 32px;
  line-height: 48px;
}
.main-text h1{
  font-size: 52px;
  line-height: 78px;
  margin-bottom:10px ;
}
.main-text p{
  font-size: 18px;
  line-height: 27px;

}
.main-text{
  width:400px ;
}
.btn-1, .btn-2{
  border-radius:8px ;
  border: 1px solid #7562E0 ;
  width: 140px;
  height: 45px;
  color: #fff;
  background-color: #181818;
}
.btn-1{
  background-color: #7562E0;
}
.main-img {
  background-color: #7562E0;
  border-radius: 50%;
  display: block;
  position: relative;     
}
aside{
  margin-top: 220px;
}
.black-line{
  display: block;
  position: relative;
  bottom: 70px;
  background-color: black;
  height:128px;
  width: 100% ;
}
.section-text{ 
  display: flex;
  align-items: center;
}
.section-text p{
  font-size: 24px;
  line-height: 36px;
  font-weight: 500;
}
.text-1{
  color: #7562E0;
  font-size: 32px;
  line-height: 48px;
  font-weight: 600;
}
.tex-2{
     font-size: 18px;
     line-height: 32px;
     font-weight: 500;
}

</style>
