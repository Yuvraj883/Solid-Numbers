<template>
<div class="container">
<div class="nav">
    <span class="logo">
      <i>  Solid Numbers</i>
    </span>
    
    <ul class="right-align">
       <li>About</li>
       <li>Team</li>
       <li>FAQ</li>
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
   
    width:60%;
    display:block;
    margin-left:7%;
}
.number img{
   
    width:40%;
    margin-right:5%;
    margin-top:5%;
    
}
.container{
    background-image: url("../assets/SOLID-NUMBERS/gradient-background.jpg");
    color:white;
    margin:0;

}
.right-align{
    text-align:right;
    display:flex;
    margin-left:auto;
    margin-right:5%;
    cursor:pointer;

    
}

.nav{
    display:flex;
    
}
li{
    list-style: none;
    margin:1em;
}
.logo{
    margin-top:1.5em;
    margin-left:7%;
    font-weight: bolder;
}
</style>