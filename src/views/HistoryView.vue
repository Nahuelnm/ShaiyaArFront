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
          <div id="aboutSh">
            <aboutSh msg="aboutSh"/>
          </div>

      </div>
        <socialBar msg="socialBar"/>
    </div>
  <div >    


  </div>
    </template>
    <script>
    import registerBar from '../components/registerBar.vue';
    import navBar from '../components/navBar.vue';
    import aboutSh from '../components/history.vue';
    import socialBar from '../components/socialBar'
    export default {
      name: 'HistoryView',
      components: {
        navBar,
        registerBar,
        aboutSh,
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
    