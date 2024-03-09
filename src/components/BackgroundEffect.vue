<template>
  <div class="box">
    <div></div>
    <div></div>
    <div></div>
    <div></div>
    <div></div>
    <div></div>
    <div></div>
    <div></div>
    <div></div>
    <div></div>
  </div>
</template>

<script>
</script>

<style>
  .box div{
    width: 60px;
    height: 60px;
    background-color: transparent;
    border: 6px solid #4d4d4d;
    position: absolute;
  }
  .box div:nth-child(1){
    top:2%;
    left: 42%;
    animation: animate 10s linear infinite;
  }
  .box div:nth-child(2){
    top:10%;
    left: 50%;
    animation: animate 7s linear infinite;
  }
  .box div:nth-child(3){
    top:6%;
    left: 6%;
    animation: animate 9s linear infinite;
  }
  .box div:nth-child(4){
    top:5%;
    left: 60%;
    animation: animate 9s linear infinite;
  }
  .box div:nth-child(5){
    top:10%;
    left: 10%;
    animation: animate 6s linear infinite;
  }
  .box div:nth-child(6){
    top:4%;
    left: 70%;
    animation: animate 12s linear infinite;
  }
  .box div:nth-child(7){
    top:2%;
    left: 4%;
    animation: animate 15s linear infinite;
  }
  .box div:nth-child(8){
    top:11%;
    left: 25%;
    animation: animate 16s linear infinite;
  }
  .box div:nth-child(9){
    top:6%;
    left: 25%;
    animation: animate 9s linear infinite;
  }
  .box div:nth-child(10){
    top:10%;
    left: 85%;
    animation: animate 5s linear infinite;
  }
  @keyframes animate{
    0%{
      transform: scale(0) translateY(0) rotate(0);
    }
    100%{
      transform: scale(1.3) translateY(-90px) rotate(360deg);
      opacity: 0;
    }
  }
</style>