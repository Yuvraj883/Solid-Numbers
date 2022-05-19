<template>
  <div class="container">
    <div class="number">
      <img src="../assets/SOLID-NUMBERS/2.png" alt="1" />
    </div>
    <div class="about" >
        <div>
        <img src="../assets/LoveDeep.jpeg" alt="LoveDeep"/>
        <p class="name">Love Deep kashyap</p>
        <p class="title">Founder, Deep Fake Company </p>
        <p>All I need is 1 verse to put you in a hearse, and I don't even have to put my cap on (Naa)
Kalamkaar ko bana baitha main deathrow
Iss baar iski maut tull na paaye jaise Jethro
Ending the silence with violins of violence
Now watch a dead rapper get fucked, no necro
Kulfa kya karegi kulfi hai khud, Bunty toh lagta hai buddi se dusht
Automatic tha brush, automatic ab tange
Jab dikhta hai dollar toh khulti hai khud (Khud)
Dekho ye chapri hai, soch iski naali me (Naali me)
Isko laga ye Brutal hai gaali se (Gaali se)
Mera gaana ni chala tha tere naam se
Chala mera gaana teri badnaami se</p>
</div>

    </div>
  </div>
</template>
<script>
export default{
    name:'About'
}
</script>
<style scoped>
.container {
  background-image: url("../assets/SOLID-NUMBERS/gradient-background2.jpg");
  color: white;
  margin: 0;
  display: flex;
}
.title{
    margin-top:1vh;
}
.name{
    font-weight: bolder;
    font-size:1.8em;
    margin-bottom: 0vh;
}
.about div{
    margin-top: 10vh;
    width: 80%;
    margin-left:5vw;

}
.number{
   
    width:40%;
   
    margin-top:5%;
    
}
.number img{
    height:60vh;
}
.about img{
    border-radius:50%;
    height:20vh;
    margin-bottom:.5em;
}
.about{
    padding:5vh;
      width:60%;
    display:block;
    margin-left:7%;
}
</style>