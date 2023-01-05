<template>
    <div id="body">    
        <div id="bar">
          <registerBar msg="registerBar"/>
        </div>
        
        <div id="banner">
          <a v-bind:href="'/'"> <img alt="Vue logo" src="../assets/logo.png" id="logo"></a> 
        </div>
      <div id="home">
          <div id="navBar">
            <navBar msg="navBar"/>
          </div>
          <div id="introblock">
            <introblock msg="introblock"/>
            
          </div>
          <div id="storeBar">
            <storeBar msg="storeBar"/>
          </div>
          <div id="components">  
            <HelloWorld msg="Welcome to Your Vue.js App"/>   
           </div>

      </div>
        <socialBar msg="socialBar"/>
    </div>
  <div >    


  </div>
    </template>
    <script>
    import HelloWorld from '../components/Home.vue';
    import registerBar from '../components/registerBar.vue';
    import navBar from '../components/navBar.vue';
    import storeBar from '../components/storeBar.vue';
    import introblock from '../components/introblock.vue';
    import socialBar from '../components/socialBar'
    export default {
      name: 'HomeView',
      components: {
        HelloWorld,
        navBar,
        introblock,
        registerBar,
        storeBar,
        socialBar
      }
    }
    </script>
    
    <style>
    img{
      width: 30%;
    }
    #registro{
      height: 45px;
      justify-content: center;
      text-align: right;
      border-radius: 10px;
    }
    #banner{
      margin-top:3%;
      width: 100%;
    }
    #body{
     background: url(../assets/background.jpg);
     background-size: 100% auto;
     width: 100%;
     height: 100%;
     color: black;
     background-repeat: no-repeat;
     background-color:black;
     border-radius: 10px;
    }
    #introBlock{
      width: 10%;
    }
    #components{
      margin-top: 0%;

      height: 100%;
      width: 55%;

      color: white;
      opacity: 1;
      text-align: left;
      
    }
    #bar{
          background-size: 61% auto;
    }
    #home{
      margin-left: 23%;
      background: url(../assets/body_background.png);
      background-size: 72% 100%;
      background-repeat: no-repeat;
      height: 100%;
    }
    </style>
    