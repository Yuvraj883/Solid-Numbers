<template>
<div class="container">
<div class="nav">
    <span class="logo">
      <i>  Solid Numbers</i>
    </span>
    
    <ul class="right-align">
       <li><a href="#about">About</a></li>
       <li><a href="#faq">FAQ</a></li>
       <li><a href="#team">Team</a></li>
       <li><a href="https://opensea.io/collection/solidnumbers">Mint</a></li>
    </ul>

</div>   


<div class="content">
<div class="solid">
<img src="../assets/SOLID-NUMBERS/solid-numbers.png" alt="Solid Numbers">
<button class="mint"><a href="https://opensea.io/collection/solidnumbers">Mint Now</a></button>
</div>
<div class="number">
    <img src="../assets/SOLID-NUMBERS/1.png" alt="1">
</div>
</div>
</div>

</template>
<script>
export default{
    name:'Nav'
}
</script>
<style scoped>
.mint{
  
    color:black;
    border-radius: 1em;
    padding:.2em .6em;
    margin-right:72%;
    font-size:1.5em;
    margin-bottom:1em;
    margin-bottom:1em;

}
a{
    text-decoration: none;
}
li a{
    color:white;
}
.content{
    display:flex;
}
.solid img{
   justify-content: center;
    width:60%;
    display:block;
    margin-left:7%;
    margin-top:17vh;
}
.number img{
   
    width:40%;
    margin-right:5%;
    margin-top:5%;
    height: 70vh;
    width: 30vh;
    
}
.container{
    background-image: url("../assets/SOLID-NUMBERS/gradient-background.jpg");
    color:white;
    margin:0;
    height: 100vh;

}
.right-align{
    text-align:right;
    display:flex;
    margin-left:auto;
    margin-right:5%;
    cursor:pointer;

    
}

li:hover{
  -webkit-transform: scale(1.3);
  -ms-transform: scale(1.3);
  transform: scale(1.3);
  font-weight: 900;
   transform: skew(-10deg);
}
.nav{
    display:flex;
    
}
li{
    list-style: none;
    margin:1em;
}
.logo{
    margin-top:.5em;
    margin-left:7%;
    font-weight: bolder;
    font-size:3em;
    font-family: baron-neue;
    color:	#A8A9AD;
}
</style>