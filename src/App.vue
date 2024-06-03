<script setup>
import Headdiv from './components/Headdiv.vue' 
import Cart from "./components/cart/cart.vue"
import Header from "./components/header/header.vue"
import logo1 from "./assets/PS5-Controller-PNG-Image.png"
import keyboard from "./assets/20828-2-poseidon-gaming-keyboard-mechanical.png"
import bg1 from "./img/a86af381b53feae25fbccfc06d3e8392.jpg"
import bg2 from "./img/d6571d382312c382602443bb36f6592a.jpg"
import wdbimg from "./img/Layer 1.png"
import icongame from "./img/Layer 0.png"
import bg from "./img/bg.png"
import img4 from "./img/Layer 4.png"
import logoalian from "./img/9986e5b2f3885676398e923c99d1d061.jpg"
import logoicon2 from "./img/7120d8b54420ecf41395d9c18d5ee503 (1).jpg"
import logo3 from "./img/18126fa477be8f566d8a2ea8896bf426.jpg"
import Water from "./components/footer/water.vue"
</script>
<script>
export default {
  data(){
    return{
      img1bg:`background-image:url(${bg1});`,
      bg2img:`background-image:url(${bg2});`,
      bg3img:`background-image:url(${bg});background-color:white;`
    }
  }
}
</script>
<template>
    <Header/>
    <Headdiv/>
    <br/>
    <br/>
    <br/>
    <br/>
    <div class="titlebox">
    <h1 class="title"> <span></span> Who we are ?? <span></span></h1>
    <p>Lotus is not just a computer games company
In Lotus, all kinds of up-to-date websites are built with the most up-to-date frameworks in the world
The best digital arts are made and finally computer games are designed with the most powerful technology</p>
    </div>
    <br/>
    <br/>
    <br/>
    <br/>
    <div class="cartsboxes">
    <div class="bgr"></div>
    <div class="bgl"></div>
    <div class="cartholder">
    <Cart header="Game projects" text="start some games projects with unreal 5 and learn it" :photobg="img1bg" :img="icongame"/>
    <Cart header="Web developing" text="Our web developers team have three parts : designers , Front-end , Back-end and use the Most Popular programing tech" :photobg="bg2img" :img="wdbimg"/>
    <Cart header="Digital arts" text="Make some NFT and digital Characters" :photobg="bg3img"  :img="img4"/>
    </div>
    </div>
    <br/>
    <br/>
    <br/>
    <br/>
    <h1 class="title"> <span></span> Team Lotus <span></span></h1>
    <br/>
    <br/>
    <br/>
    <br/>
    <div class="explain">
     <div class="itemex">
     <div class="logobox">
       <div class="logo">
        <Water st="background-color:#e7c0ff;"/>
       </div>
       </div>
       <div class="text">
       <h1>Learn and update your skils</h1>
        <p>At Lotus, we have a team that is always updated and ready to learn and learn new skills, and with the help of this strong team, we are able to solve all kinds of challenges.
Currently, we are building up-to-date and practical sites with the best front-end frameworks.
Also, our team has the necessary strength in the construction and design of the system and the use of the sites.
Also, we have used various artificial intelligence tools in various fields of schematics of sites and software. For example, we will use AR technology to display items such as furniture, carpets, and home appliances, and we will deliver a live and very useful website or web application to you and your business.
Projects are carried out in different steps, the number and type of steps will vary depending on the employer's goal</p>
        <button>more</button>
       </div>
     </div>
     <div class="itemex">
       <div class="text">
       <h1>Our team and Experience of personnel </h1>
        <p>Professionalism of employees in a programming company is very important. These companies are looking for employees who have technical abilities and the necessary skills in the field of programming.
First, a professional employee in the programming company must have a fair amount of technical knowledge. This includes familiarity with different programming languages, experience in using different tools and frameworks, and the ability to solve complex problems.
In addition to technical knowledge, the second step in employee professionalism is practical experience. How long have they experienced working with real projects? Are they able to manage large projects? Do they have the ability to work with the team? These are important questions that show that employees are ready to perform their duties. </p>
        <button style="background-color: #67e9ff;    box-shadow: #67e9ff 0px 0px 5px 0px; ">our team CVs</button>

       </div>
       <div class="logobox">
       <div class="logo">
        <Water/>
       </div>
       </div>
     </div>
     <div class="itemex">
     <div class="logobox">
       <div class="logo">
        <Water st="background-color:#ffc107;"/>
       </div>
       </div>
       <div class="text">
        <h1>Our relationship with the latest programming technologies</h1>
        <p>In today's world, today's knowledge allows programmers to perform their tasks with ease and confidence. With the advancement of technology and the development of programming languages, the process of writing codes has improved significantly.
The third reason for being comfortable with current knowledge of programming is the community of programming languages. Modern languages ​​such as Python, JavaScript, and Ruby allow programmers to easily write their code using a simple and understandable syntax. Since the Lotus team uses the most up-to-date programming tools, there is no need to worry about the development of artificial intelligence or other languages.</p>
    <button style="background-color: #fec007;">our options</button>
       </div>
     </div>
    </div>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    <div class="waterdiv">
    <h1>This is us ! Lotus designers</h1>
  </div>
</template>

<style scoped>
 @import "./css/main.css";
</style>
