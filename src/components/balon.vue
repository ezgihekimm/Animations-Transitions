<template>
    <div class="hero" :style="{'background-image': 'url(' + require('../../public/assets/images1/slider4.jpg') + ')'}">
       
       <div class="balon">
           <img :src="require('../../public/assets/images1/bubble.png')" alt="">
             <img :src="require('../../public/assets/images1/bubble.png')" alt="">
               <img :src="require('../../public/assets/images1/bubble.png')" alt="">
                 <img :src="require('../../public/assets/images1/bubble.png')" alt="">
                   <img :src="require('../../public/assets/images1/bubble.png')" alt="">
                     <img :src="require('../../public/assets/images1/bubble.png')" alt="">
                       <img :src="require('../../public/assets/images1/bubble.png')" alt="">
           
       </div>
       <div class="div text-center mt-3">
           <h1 style="font-size:100px;font-family: 'Roboto', sans-serif; color:#C4E5F6; opacity:50%;">BAUMIND</h1>
       </div>



    </div>



</template>

 <script>
  export default{
      data: function(){

          return{
               show:true 
          }
        
      }
  }
 </script>
 


<style scoped>
.hero{
    width: 100%;
    height: 50vh;
    background-size: cover;
    background-position: center;
    position: relative;
    overflow: hidden;

}
.balon img{
    width: 50px;
    animation: balon 7s linear infinite;
}
.balon{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-around;
    position: absolute;
    bottom: 0;
}
@keyframes balon {
    0%{
        opacity: 0;
        transform: translateY(0);
    }
    50%{
        opacity: 1;
    }
    70%{
        opacity: 1;
    }
    100%{
        opacity: 0;
        transform: translateY(-80vh);
    }

    
}
.balon img:nth-child(1){
animation-delay: 2s;
}
.balon img:nth-child(1){
animation-delay: 2s;
}
.balon img:nth-child(2){
animation-delay: 1s;
}
.balon img:nth-child(3){
animation-delay: 3s;
}
.balon img:nth-child(4){
animation-delay: 4.5s;
}
.balon img:nth-child(5){
animation-delay: 3s;
}
.balon img:nth-child(6){
animation-delay: 7s;
}
.balon img:nth-child(7){
animation-delay: 6s;
}
</style>