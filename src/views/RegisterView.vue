<template>
  <div id="bodyR">    
      <div id="bar">
        <registerBar msg="registerBar"/>
      </div>
    <div id="homeR">
      <div>      

      </div>
        <div id="aboutSh">
          <register msg="register"/>
        </div>

    </div>

  </div>
<div >    


</div>
  </template>
  <script>
  import register from '../components/register.vue';
  export default {
    name: 'RegisterView',
    components: {
      register,
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
  }
  #banner{
    margin-top:3%;
    width: 100%;
  }
  #body{
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
  </style>
  