<template>
<div class="container">
<div class="number">
    <img src="../assets/SOLID-NUMBERS/4.png" alt="4"/>
    
</div>
<div class="team">
    <div>
        <img src="../assets/LoveDeep.jpeg" alt="LoveDeep"/>
        <p class="name">Love Deep Kashyap</p>
        <p class="title">CEO</p>
        </div>

         <div>
        <img src="../assets/LoveDeep.jpeg" alt="LoveDeep"/>
        <p class="name">Kanno<b>&#9829;</b>
</p>
        <p class="title">Designer</p>
        </div>

         <div>
        <img src="../assets/LoveDeep.jpeg" alt="LoveDeep"/>
        <p class="name">Love Deep Kashyap</p>
        <p class="title">CEO</p>
        </div>

         <!-- <div>
        <img src="../assets/LoveDeep.jpeg" alt="LoveDeep"/>
        <p class="name">Love Deep Kashyap</p>
        <p class="title">CEO</p>
        </div>
         <div>
        <img src="../assets/LoveDeep.jpeg" alt="LoveDeep"/>
        <p class="name">Love Deep Kashyap</p>
        <p class="title">CEO</p>
        </div> -->

       
</div>
<div></div>

</div>
</template>
<script>
export default{
    name:'Team'
}
</script>
<style scoped>
.name b{
    color:red;
   
}
.team div{
    width: 33%;
}
.team{
    display:flex;
    flex-wrap:wrap;
    margin:auto;

}
.title{
    margin-top:1vh;
}
.name{
    font-weight: bolder;
    font-size:1.5em;
    margin-bottom: 0vh;
}
.team img{
    border-radius: 50%;
    height: 10vh;
    
    margin-bottom:0em;
}
.container {
  background-image: url("../assets/SOLID-NUMBERS/gradient-background2.jpg");
  color: white;
  margin: 0;
  display: flex;
}
.number img{
   
    width:40%;
    margin-right:5%;
    margin-top:5%;
    
}
</style>