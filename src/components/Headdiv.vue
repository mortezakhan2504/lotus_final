<script>
import vid1 from "../img/doc_2023-09-10_01-50-50.gif"
import vid2 from "../img/doc_2023-09-10_01-50-50.gif"
import vid3 from "../img/doc_2023-09-10_01-51-01.gif"
import vid4 from "../img/doc_2023-09-10_01-51-08.gif"
import vid5 from "../img/doc_2023-09-10_01-51-12.gif"
import vid6 from "../img/doc_2023-09-10_01-51-19.gif"
import vid7 from "../img/doc_2023-09-10_01-51-25.gif"
export default {
    data(){
        return {
            pinkdiv:"",
            blackdiv:""
            ,array:[
              {
                "partners":"icon",
                'text':`Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
                "link":"#",
                "vid":vid1
              },
              {
                "partners":"icon",
                'text':`Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
                "link":"#",
                "vid":vid2

              },
              {
                "partners":"icon",
                'text':`Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
                "link":"#",
                "vid":vid3

              },
              {
                "partners":"icon",
                'text':`Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
                "link":"#",
                "vid":vid4

              },
              {
                "partners":"icon",
                'text':`Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
                "link":"#",
                "vid":vid5

              },
              {
                "partners":"icon",
                'text':`Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
                "link":"#",
                "vid":vid6

              },
                {
                "partners":"icon",
                'text':`Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
                "link":"#",
                "vid":vid7

              },
            ]
        }
    }
    ,methods: {
        chanfgepingdiv (e){
            console.log(e)
            this.pinkdiv = `width: ${e.clientX}px;`
        },
        playvid(e){
          e.target.play()
        },
        puse(e){
          e.target.pause()
        }
    },
}
</script>


<template>

<div class="headbox" @mousemove='chanfgepingdiv'>

    <div class="pinkdiv"  :style=pinkdiv>
      <span id="dblack" class="logo">Lotus</span>
      <h1><span id="dblack">Lotus</span> designers</h1>
      <div class="itembox">
      <div v-for="item in array" class="item">
         <div class="headitem">
          <div class="profile"></div>
          <span>{{item.partners}}</span>
         </div>
         <div class="body">
          <img :src="item.vid"/>
         </div>
         <div class="link"></div>
      </div>
     
      </div>
    </div>
    <div class="blackdiv" >
      <span id="dblack" class="logo">Lotus</span>
      <h1>Lotus <span id="dblack">designers </span></h1>
      <div class="itembox">
       <div v-for="item in array" class="item">
         <div class="headitem">
          <div class="profile">
             
          </div>
          <span>{{item.partners}}</span>
         </div>
         <div class="body">
          <img :src="item.vid"/>
         </div>
         <div class="link"></div>
      </div>
    </div>

    </div>
</div>

</template>

<style scoped>
    @import "./Headdivcss/main.css"
</style>