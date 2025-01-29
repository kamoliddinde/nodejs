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
      <Sectiontitle title="About me:"/>
      <p class="text-2">Hi, my name is Jayjay Dinero Dinero, i am a Fullstack web developer, UI designer, and Mobile developer. I jhave honed my skills in Web Development and advance i have core understanding of advance UI design principles. 
        Here are the major skiills i have. </p>
      <div class="section-text">
       
        <img src="@/assets/images/5+.png" alt="">
        <p>Years of experience. Specialised in building apps, while ensuring a seamless
          web experience for end users.</p>
      </div>
      <div class="cards">
        <TheCard title="UI UX designing" :img="card1" className="active"/>
        <TheCard title="Web development" :img="card1"/>
        <TheCard title="Mobile Development" :img="card1"/>
        <TheCard title="Web scraping with " :img="card1"/>
      </div>
    
    </div>
  </section>
  <section>
    <div class="container">
        <Sectiontitle title="The services i offer:"/>
        <div class="services">
          <ServicesCard
          title="UI UX designing"   
          text=" Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda, ea."
          :img="card1"
          variant="var1"

          />
          <ServicesCard 
          title="Web developmen"
          text=" Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda, ea."
          :img="card1"
          variant="var2"
          />
          <ServicesCard
          title="UI UX designing" 
          text=" Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda, ea."
          :img="card1"
          variant="var1"

          />
          <ServicesCard 
          title="Web developmen"
          text=" Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda, ea."
          :img="card1"
          variant="var2"
          />
          <ServicesCard
          title="UI UX designing" 
          text=" Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda, ea."
          :img="card1"
          variant="var1"

          />
          <ServicesCard 
          title="Web developmen"
          text=" Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda, ea."
          :img="card1"
          variant="var2"
          />
       
        </div>
      </div>

  </section>
  <section>
    <div class="container">
      <div class="FeaturProjects">
        <Sectiontitle title="Featured projects:"/>
        <p>I have worked on many projects over the course of being a Web Developer, here are a few of my live, real-world projects</p>
      <div class="projects">
        <FeaturedProjects :img="map" title="TWINDER" text="A live Geolocation app for finding tweets and twitter users around you."  />
       <FeaturedProjects :img="live" title="LIVENTS" text="A video streaming app with live Geolocation, for streaming events." />
       <FeaturedProjects :img="car" title="MOOVE" text="Mobile app for booking instant pickup & dropoff accross major cities."  />
      </div>
      </div>

    </div>
  </section>
  <section>
    <div class="container">
      <div class="contacts">
        <div>
          <Sectiontitle title="Contact With me:"/>
          <p>Satisfied with me? Please contact me</p>
          <BrandLink/>
        </div>
        <div>
          <h2>Contact me, let’s make magic together</h2>
          <div class="input">
            <input class="input-1" type="text" placeholder="Name:">
            <input class="input-2" type="text" placeholder="Email:">
            <input class="input-3" type="text" placeholder="Message:">
          </div>
          <button class="btn-1">
            <p>Send</p>
          </button>
        </div>
      </div>
    </div>
  </section>   
</template>
<script setup>
import TheCard from "@/components/TheCard.vue"; 
import Sectiontitle from "@/components/SectionTitle.vue";
import ServicesCard from "@/components/ServicesCard.vue";
import FeaturedProjects from "@/components/FeaturedProjects.vue";
import BrandLink from "@/components/BrandLink.vue";
import map from "@/assets/images/map.png"
import card1 from "@/assets/images/card-1.png"; 
import live from "@/assets/images/Live.png"
import car from "@/assets/images/Car.png"
</script>
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
  font-size: 42px;
  line-height: 50px;
  margin-bottom:10px ;
}
.main-text p{
  font-size: 18px;
  line-height: 27px;

}
.main-text{
  width:450px ;
  margin-top: 160px;
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
.main-img{
  margin-bottom: -80px;
  margin-top: 200px;
  width: 400px;
}
.black-line{
  display: block;
  position: relative;
  bottom: 70px;
  background-color:#181824 ;
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
.tex-2{
     font-size: 18px;
     line-height: 32px;
     font-weight: 500;
}
.cards{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  gap: 20px;
 margin-top: 40px;
}
.project{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 20px;
}
.contacts{
  display: grid;
  grid-template-columns: 1fr 1fr ;
  gap: 20px;
}
.input{
 
}
.input-1, .input-2 {
  width: 100%;
  height: 62px;
  background-color: #31313F;
  border: none;
  border-radius: 8px;
  margin: 8px;
}
.input-3{
  width: 100%;
  height: 98px;
  background-color: #31313F;
  border: none;
  border-radius: 8px ;
  margin: 8px;
}
.btn-1{
   margin-left : 8px;
}
</style>
