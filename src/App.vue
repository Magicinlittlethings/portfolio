<template lang = "html" class="  ">
<div class="relative">
 <div v-if="showMenu" class=" flex justify-center  bg-black opacity-90 z-100 absolute h-screen w-screen pt-4 lg:hidden " style="color:white;`">
      
        <button @click="showMenu = !showMenu" class="absolute right-8"><fa icon="times" class=" text-3xl text-gray-100 hover:text-bora" /></button>
      

        
      <div class="flex-col pt-12">
        <a href="#home" @click="id = 'home'"  :class="` ${ id === 'home' ?  'text-bora' : '' }   hover:text-gray-400 text-lg md:text-xl font-semibold mb-6 md:mb-8 block text-center`">HOME</a>
        <a href="#professional" @click="id = 'professional'"  :class="` ${ id === 'professional' ?  'text-bora' : '' }   hover:text-gray-400 text-lg md:text-xl font-semibold mb-6 md:mb-8 block text-center`">PROFESSIONAL</a>
         <a href="#portfolio" @click="id = 'portfolio'"  :class="` ${ id === 'portfolio' ?  'text-bora' : '' }   hover:text-gray-400 text-lg md:text-xl font-semibold mb-6 md:mb-8 block text-center`">PORTFOLIO</a>
         <a href="#experience" @click="id = 'experience'"  :class="` ${ id === 'experience' ?  'text-bora' : '' }   hover:text-gray-400 text-lg md:text-xl font-semibold mb-6 md:mb-8 block text-center`">EXPERIENCE</a>
         <a href="#contact" @click="id = 'contact'"  :class="` ${ id === 'contact' ?  'text-bora' : '' }   hover:text-gray-400 text-lg md:text-xl font-semibold mb-4 block text-center`">CONTACT</a>
      </div>
  </div>
  <div class="hero  bg-black w-screen " id="home">
     <div class="flex justify-end  pr-8 py-2 w-screen shadow-sm bg-gray-800  lg:hidden">
      
      <button @click="showMenu = true"> <fa  icon="bars" class=" text-2xl text-gray-100 hover:text-bora" /> </button>
       
    </div>
    
    <div class="hidden lg:block ">
     <div class=" flex justify-between    fixed  py-4 px-60  w-screen shadow-md  bg-black  z-50 " style="color:white;">
      
        <a href="#home" @click="id = 'home'"  :class="` ${ id === 'home' ?  'text-bora' : '' }   hover:text-gray-400 text-base font-semibold`">HOME</a>
        <a href="#professional" @click="id = 'professional'"  :class="` ${ id === 'professional' ?  'text-bora' : '' }   hover:text-gray-400 text-base font-semibold`">PROFESSIONAL</a>
         <a href="#portfolio" @click="id = 'portfolio'"  :class="` ${ id === 'portfolio' ?  'text-bora' : '' }   hover:text-gray-400 text-base font-semibold`">PORTFOLIO</a>
         <a href="#experience" @click="id = 'experience'"  :class="` ${ id === 'experience' ?  'text-bora' : '' }   hover:text-gray-400 text-base font-semibold`">EXPERIENCE</a>
         <a href="#contact" @click="id = 'contact'"  :class="` ${ id === 'contact' ?  'text-bora' : '' }   hover:text-gray-400 text-base font-semibold`">CONTACT</a>
       
     </div>
     
    </div>
    
    
    
   
    <div class="flex justify-center bg ">
      
      <div class="">
        
      <p class="text-gray-100 text-5xl lg:text-8xl font-semibold pt-48 leading-tight text-center">
        <transition-group  appear @before-enter="typee1" @enter="type1"><span class="type1"> I<span class="text-bora">'</span>M</span></transition-group> 
        <br>
        <transition name="typewriter2"> <span class="type2">LAWAL </span></transition>
        <br>
       <transition name = "typewriter3"> <span class= "type3"> KHADIJAT<span class="text-bora">.</span></span></transition>
         <br>
         <transition name="typewriter4"><span class=" type4 text-3xl lg:text-4xl font-normal  ">FRONT END WEB DEVELOPER</span></transition>
         </p>
     </div>
     
    </div>
    
    
   
  </div>
  <div class="second  flex justify-center relative w-screen">
    <div class=" card absolute bg-gray-800 p-8 lg:p-16 w-3/5 ">
      <p class="font-bold text-3xl  lg:text-4xl text-center text-gray-100 mb-8">ABOUT <span class=" text-bora">ME</span></p>
      <p class="text-center text-gray-100  lg:px-20 leading-loose">
        Hi, My name is Lawal Khadijat Gbemisoke, Nice to meet you.<br> I'm a Freelance Front-End Web Developer in Lagos, Nigeria. I have  passion for UI effects, animations and creating intuitive, dynamic user experiences.

      </p>
      <p class="mt-28 text-center"><a href="contact" class="text-center text-bora  text-semibold">Let's make something special</a></p>
      
      <div class="flex justify-center">
         <a href="https://drive.google.com/file/d/1EE5Ogv3YM9kwxCxFcQ-pUscBGIgyq9QX/view?usp=sharing" class=" mx-auto border border-rounded border-bora hover:bg-bora text-gray-100 mt-8 p-2 font-semibold">DOWNLOAD RESUME</a>
      </div>
     
    </div>
    <div class=" mt-96 " id="professional">
      <p class="professional text-gray-100 font-semibold text-4xl lg:text-7xl mb-2 text-center"><span class="text-gray-400">01</span> PROFESSIONAL</p>
      <p class="text-gray-100 text-xl lg:text-2xl text-center">MY KNOWLEDGE IN SOFTWARE</p>
      <div class="flex-col pb-36 hidden lg:block">
        <div class="flex mt-12  ">
          <p class="text-lg text-gray-100">HTML</p>
          <div class="flex justify-between ml-8 ">
           <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress1 bg-bora h-4 mt-1.5 mr-2 "></div>
           </transition>
            <div class="percentage text-lg text-gray-100">90%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-lg text-gray-100">CSS</p>
          <div class="flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress2 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-lg text-gray-100">80%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-lg text-gray-100">TAILWINDCSS</p>
          <div class="flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress3 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-lg text-gray-100">90%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-lg text-gray-100">JAVASCRIPT</p>
          <div class="flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress4 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-lg text-gray-100">70%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-lg text-gray-100">GSAP</p>
          <div class="flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress5 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-lg text-gray-100">75%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-lg text-gray-100">VUE JS</p>
          <div class="flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress6 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-lg text-gray-100">50%</div>
          </div>
          
        </div>
      </div>
      <div class="flex-col pb-36 lg:hidden">
        <div class="flex mt-12  ">
          <p class="text-base text-gray-100">HTML</p>
          <div class="flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress1 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-base text-gray-100">90%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-base text-gray-100">CSS</p>
          <div class="flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress2 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-base text-gray-100">80%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-base text-gray-100">TAILWINDCSS</p>
          <div class="flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress3 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-base text-gray-100">90%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-base text-gray-100">JAVASCRIPT</p>
          <div class="flex justify-between ml-8 ">
          <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress4 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-base text-gray-100">70%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-base text-gray-100">GSAP</p>
          <div class="flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress5 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-base text-gray-100">75%</div>
          </div>
          
      </div>
         <div class="flex mt-8 ">
          <p class="text-base text-gray-100">VUE JS</p>
          <div class="flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress6 bg-bora h-4 mt-1.5 mr-2 "></div>
            </transition>
            <div class="percentage text-base text-gray-100">50%</div>
          </div>
          
        </div>
      </div>
    </div>
  </div>
  <div class="third flex-col justify-center pt-32 pb-96 w-screen" id="portfolio">
     <p class="text-gray-100 font-semibold text-4xl lg:text-7xl mb-2 text-center"><span class="text-gray-400">02</span> PORTFOLIO</p>
      <p class="text-gray-100 text-xl lg:text-2xl text-center">MY LATEST WORK.  </p>
      <div class="mt-16 mb-36  flex-col  px-8">
        <div class=" flex justify-center mb-4">
          <div class="w-3/5 bg-bora border border-transparent rounded-full py-3 text-gray-100 hover:text-bora  hover:border-bora flex justify-center hover:bg-transparent hover:scale-110 ease-in-out duration-300">
          <a href="https://nokosocialsite.netlify.app/" class="text-lg text-center font-semibold"> NOKOSOCIAL</a>
         </div>
        </div>
         <div class=" flex justify-center mb-4">
          <div class="w-3/5 bg-bora border border-transparent rounded-full py-3 text-gray-100 hover:text-bora  hover:border-bora flex justify-center hover:bg-transparent hover:scale-110 ease-in-out duration-300">
          <a href="https://twittter-clone.netlify.app/" class="text-lg text-center font-semibold"> TWITTER-CLONE</a>
         </div>
        </div>
        <div class=" flex justify-center mb-4">
          <div class="w-3/5 bg-bora border border-transparent rounded-full py-3 text-gray-100 hover:text-bora  hover:border-bora flex justify-center hover:bg-transparent hover:scale-110 ease-in-out duration-300">
          <a href="https://pinterestt-clone.netlify.app/" class="text-lg text-center font-semibold"> PINTEREST-CLONE</a>
         </div>
        </div>
        <div class=" flex justify-center mb-4">
          <div class="w-3/5 bg-bora border border-transparent rounded-full py-3 text-gray-100 hover:text-bora  hover:border-bora flex justify-center hover:bg-transparent hover:scale-110 ease-in-out duration-300">
          <a href="https://fooddwebsite.netlify.app/" class="text-lg text-center font-semibold"> FOOD-SITE</a>
         </div>
        </div>
        <div class=" flex justify-center mb-4">
          <div class="w-3/5 bg-bora border border-transparent rounded-full py-3 text-gray-100 hover:text-bora  hover:border-bora flex justify-center hover:bg-transparent hover:scale-110 ease-in-out duration-300">
          <a href="https://moneydashh.netlify.app/" class="text-lg text-center font-semibold"> MONEY DASH</a>
         </div>
        </div>
        <div class=" flex justify-center mb-4">
          <div class="w-3/5 bg-bora border border-transparent rounded-full py-3 text-gray-100 hover:text-bora  hover:border-bora flex justify-center hover:bg-transparent hover:scale-110 ease-in-out duration-300">
          <a href="https://popify.netlify.app/" class="text-lg text-center font-semibold"> POPIFY </a>
         </div>
        </div>
        <div class=" flex justify-center mb-4">
          <div class="w-3/5 bg-bora border border-transparent rounded-full py-3 text-gray-100 hover:text-bora  hover:border-bora flex justify-center hover:bg-transparent hover:scale-110 ease-in-out duration-300">
          <a href="https://pizzagsap.netlify.app/" class="text-lg text-center font-semibold"> PIZZA-GSAP </a>
         </div>
        </div>
        
        
      </div>
      <div class="flex-col justify-center  px-24 lg:px-40" id="experience">
        <p class="text-gray-100 font-semibold text-4xl lg:text-7xl mb-2 text-center "><span class="text-gray-400">03</span> EXPERIENCE</p>
        <div class="h-full mt-16 flex justify-between">
          <div class="mt-28">
            <p class="text-bora text-base mb-2"> 2021 - 2022</p>
            <p class="text-gray-100 text-2xl mb-5">CODEBASE TECHNOLOGIES</p>
            <p class="text-gray-400 text-base font-semibold">Intern</p>
            
          </div>
          <div class="w-1 bg-bora border border-bora mx-8 rounded-2xl" ></div>
          <div >
            <p class="text-bora text-base mb-2"> 2022 - PRESENT</p>
            <p class="text-gray-200 text-2xl mb-5">OURANOS TECHNOLOGIES</p>
            <p class="text-gray-400 text-base font-semibold">Intern</p>
            
          </div>
        </div>
      
      </div>

  </div>
  <div class="fourth relative flex justify-center h-screen w-screen" id="contact">
   <div class=" card2 absolute bg-gray-800 p-8 lg:p-16  w-3/5   ">
    <div class="lg:flex lg:justify-between">
     <div class="">
       <p class="text-gray-100 text-2xl mb-5 lg:mb-0 text-center lg:text-left ">CONTACT</p>
       <p class="py-5 text-gray-100 text-base lg:block hidden"></p>
       <p class="text-gray-100 font-semibold lg:block hidden  " >ladeholar@gmail.com</p>
       <p class="text-gray-100 font-semibold lg:block hidden">+2347019849395</p>
     </div>
     <div>
       <form>
         <div class="flex mb-2">
           <input type="text" placeholder=" Name" class="w-full h-12 pl-2 border hover:border-bora mr-1.5">
           <input type="email" placeholder="Email" class="w-full h-12 pl-2 border hover:border-bora ml-1.5">
         </div>
         <input type="text" placeholder="Phone" class="w-full h-12 mb-2 pl-2 border hover:border-bora ">
         <input type="text" placeholder="Message" class="w-full h-40 mb-2 pl-2 border hover:border-bora py-0 ">
         <input type="submit" placeholder="Send" class="w-full h-12 text-center border border-transparent text-gray-100 bg-bora hover:bg-gray-200 hover:text-bora">
       </form>
     </div>
    </div>
     
     <div class="flex justify-center  mt-12">
      <a href="https://www.linkedin.com/in/lawalkhadijat/"><fa :icon="['fab', 'linkedin']" class="lg:text-2xl text-xl hover:scale-90 pr-3 lg:pr-5 text-white"/></a>
      <a href="https://www.instagram.com/_theblackchild/"><fa :icon="['fab', 'instagram']" class="lg:text-2xl text-xl hover:scale-90 pr-3 lg:pr-5 text-white"/></a>
      <a href="https://www.twitter.com/adeholarlawal/"><fa :icon="['fab', 'twitter']" class="lg:text-2xl text-xl hover:scale-90 pr-3 lg:pr-5 text-white"/></a>
      <a href="https://www.github.com/magicinlittlethings/"><fa :icon="['fab', 'github']" class="lg:text-2xl text-xl hover:scale-90 pr-3 lg:pr-5 text-white"/></a>
    </div>
    </div>
    
  </div>
  <div class="footer w-full bg-gray-800 py-6 flex justify-center w-screen">
    <p class="text-gray-100 text-base"> © 2022 by Lawal Khadijat.</p>
  </div>
</div>
</template>

<script>

import gsap from 'gsap';
import ScrollTriggerPlugin from 'gsap/ScrollTrigger.js';
gsap.registerPlugin(ScrollTriggerPlugin);
export default {
  components: {
    
  },
 
  data(){
    return{
      id:'home',
      showMenu:false,
    links:[
    {title:'HOME', nav:'#home', id:'home'},
    {title:'PROFESSIONAL', nav:'#professional', id:'professional'},
    {title:'PORTFOLIO', nav:'#portfolio', id:'portfolio'},
    {title:'EXPERIENCE', nav:'#experience', id:'experience'},
    {title:'CONTACT', nav:'#contact', id:'contact'},
  ],
  
  }
    
  },
  methods:{
    beforeEnter(el){
    width:0;
  },
    enter(el){
    gsap.from(el,{
      width:0,
      duration:2,
      
      scrollTrigger:{
          trigger:".professional",
          start: "top 50%",
          
          
    }
     })
  },
  
  
  }
 
  
}
</script>

<style>
::-webkit-scrollbar{
width:12px;
background:black;
 
}
::-webkit-scrollbar-thumb{
background:linear-gradient(transparent, rgb(104, 95, 95));
border-radius: 4px;
 
}
::-webkit-scrollbar-thumb:hover{
background:linear-gradient(transparent, #b5838d);
border-radius: 6px;
 
}
body{
overflow-x: hidden;
 
}
.hero{
height:170vh;
 
}
.second{
background-image: url(C:\Users\BLACKGIRL\Documents\vue-calculator\public\bg3.jpg);
background-size: cover;
background-attachment: fixed;
background-repeat: no-repeat;
 
}
.card{
top:-280px;
 
}
.card2{
top:-250px;
 
}
.progress1{
width:45rem;
 
}
.progress2{
width:40rem;
 
}
.progress3{
width:45rem;
 
}
.progress4{
width:35rem;
 
}
.progress5{
width:37.5rem;
 
}
.progress6{
width:25rem;
 
}
.pprogress1{
width:25rem;
 
}
.pprogress2{
width:22rem;
 
}
.pprogress3{
width:25rem;
 
}
.pprogress4{
width:18rem;
 
}
.pprogress5{
width:20rem;
 
}
.pprogress6{
width:10rem;
 
}
.third{
background-image: url(C:\Users\BLACKGIRL\Documents\vue-calculator\public\bg2.jpg);
background-size: cover;

background-repeat: no-repeat;
 
}
.fourth{
background-image: url(C:\Users\BLACKGIRL\Documents\vue-calculator\public\bg1.jpg);

background-size: cover;
background-attachment: fixed;
background-repeat: no-repeat;
 
}
.work::before{
    
    content:'';
    position: absolute;
   width:100%;
   height:100%;
    background: linear-gradient(to right, #42275a, #734b6d); 
    opacity: 0.5;
    border-radius: 0.375rem;
   
}


</style>
