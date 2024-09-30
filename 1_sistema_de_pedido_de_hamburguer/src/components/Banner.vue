<template>
    <div id="main-banner">
      <h1>Make Your Burger</h1>
    </div>
  </template>
  
  
  <script>
    export default {
      name: "Banner",
      data(){
        return{
            caminhoImagem:'/img/burger.jpg'
        }
      }
    }
  </script>
  
  <style scoped>
    #main-banner {
        background-image: url('/public/img/burger.jpg');
        background-position: right bottom -255px;
        background-size: cover;
        background-repeat: no-repeat;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }
    #main-banner h1 {
        color: #fff;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 0px 10px;
    }
    @media (max-width: 1061px) {
        #main-banner {
            background-position: right bottom;
            align-items: start;
        }
        #main-banner h1{
            margin: 20px;
            margin-left: 40px;
        }
    }
</style>
