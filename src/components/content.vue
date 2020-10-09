<template>
    <section class="section1">
   <div class="div-left"><h1>Best discounts on software you love under one shop</h1>
   <p>We, at Crisptag Technologies (A  Startup India recognised startup and incubated by NASSCOM 10,000 Startups) have partnered with Google, Microsoft, Namecheap, ZOHO, Freshworks to provide you best discounts on software under one shop.</p>
   </div>
    <div class="div-right">
        <img class="img1" src="../assets/Home-page-new.png" >
    </div>
     </section>   
</template>

<script>
export default {
    name:'Content'
}
</script>

<style lang="scss" scoped>
   section[class="section1"]{
       overflow: auto;
       display: flex;
       background-image: linear-gradient(to left,cyan, rgb(27, 7, 207));
       justify-content: center;
       align-items: center;
       div[class="div-left"]{
           flex:6;
           display: block;
           color: white;
          // border: 1px solid black;
           margin-left: 40px;
         
           h1{
               
             
               width:80%;
              height: auto;
          
              text-align: start;
           font-family: varela round,Sans-serif;
           font-size: 45px;
           font-weight: 300;
          margin-bottom: 20px;
        // text-transform: capitalize;
        // line-height: 1.4em;;
           }
           p{
            
               width:80%;
              height: auto;
           text-align : start;
           font-family: varela round,Sans-serif;
           font-size: 16px;
           font-weight: lighter;
          margin-top: 10px;
          font-family: montserrat,Sans-serif;
          line-height: 1.6em;
        // padding-top:15px;
         
           }
       }
       div[class="div-right"]{
           flex:6;
           display: flex;
        //  border: 1px solid red;
          justify-content: space-around;
          align-items: center;
          padding-right: 5%;
          margin-top:30px;
           img[class="img1"]{
               width: 85%;
               height:500px;
               border-radius: 74% 26% 10% 26% / 54% 24% 16% 14% ;
           }
       }
       
       @media only screen and (max-width: 767px){
           display: block;
       }


   }
</style>