<template>
    <div id="body">    
        <div id="bar">
          <registerBar msg="registerBar"/>
        </div>
        <div id="banner">
          <img alt="Vue logo" src="../assets/logo.png" id="logo">    
        </div>
        <div id="navBar">
          <navBar msg="navBar"/>
        </div>
        <div id="components">  
          <HelloWorld msg="Welcome to Your Vue.js App"/>   
        </div>
        <socialBar msg="socialBar"/>
    </div>
    </template>
    <script>
    import HelloWorld from '../components/Home.vue';
    import registerBar from '../components/registerBar.vue';
    import navBar from '../components/navBar.vue';
    import socialBar from '../components/socialBar'
    export default {
      name: 'HomeView',
      components: {
        HelloWorld,
        navBar,
        registerBar,
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
      background-color: rgb(27, 75, 172);
      justify-content: center;
    }
    #banner{
      margin-top:50px;
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
    #registro{
      text-align: right;
      border-radius: 10px;
    }
    #components{
      margin-top: 20px;
      margin-left: 20%;
      color: white;
      opacity: 1;
      width: 55%;
      border-radius: 10px;
      text-align: left;
      
    }
    #bar{
          background-size: 61% auto;
    }
    </style>
    