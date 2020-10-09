<template>
  <header class="header">
    <section class="section1">
      <p class="p1">
        List your SaaS Software at Crisptag-A Software Marketplace. *We charge
        no commissions*
      </p>
      <div class="div1">
        <a class="anchor1" href="#">Click here to list your SaaS Product</a>
      </div>
    </section>

    <nav class="nav2">
      <p class="p2">
        <i class="fa fa-map-marker" aria-hidden="true"></i> C-25, Sector 8,
        Noida, Uttar Pradesh 201301
      </p>
      <a class="anchor2" href="#"
        ><i class="fa fa-whatsapp" aria-hidden="true"></i> +91-85 06 02 88 88
      </a>
      <a class="anchor2" href="#"
        ><i class="fa fa-envelope" aria-hidden="true"></i> saas@crisptag.com</a
      >
      <a class="anchor2" href="#"
        ><i class="fa fa-linkedin" aria-hidden="true"></i> company/crisptag</a
      >
    </nav>

    <section class="section3">
      <img class="img3" src="../assets/crisptag_logo.png" />
      <nav class="nav3" >
        <a class="anchor3" href="#"
          >Our Offerings
          <div class="div3"></div
        ></a>
        <a class="anchor3" href="#"
          >Membership Plans <i class="fa fa-caret-down" aria-hidden="true"></i>
          <div class="div3"></div>
          <div class="display-content">
            <a href="#">Startup Plan</a>
            <a href="#">Gold Plan</a>
            <a href="#">Silver Plan</a>
          </div></a
        >
        <a class="anchor3" href="#"
          >Why We?
          <div class="div3"></div
        ></a>
        <a class="anchor3" href="#"
          >About Us <i class="fa fa-caret-down" aria-hidden="true"></i>
          <div class="div3"></div>
          <div class="display-content">
            <a href="#">Our Partnerships</a>
          </div></a
        >
        <a class="anchor3" href="#"
          >Blogs
          <div class="div3"></div
        ></a>
      </nav>
      
      <a href="#" class="menu3" v-on:click="myFunction()">
        <i class="fa fa-bars" aria-hidden="true"></i>
      </a>
      <div :id="toggle && 'dropdown-content'" class="dropdown-content">
    <!-- <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a> -->
    <a class="anchor3" href="#"
          >Our Offerings
          <div class="div3"></div
        ></a>
        <a class="anchor3" href="#"
          >Membership Plans <i class="fa fa-caret-down" aria-hidden="true"></i>
          <div class="div3"></div>
          <div class="display-content">
            <a href="#">Startup Plan</a>
            <a href="#">Gold Plan</a>
            <a href="#">Silver Plan</a>
          </div></a
        >
        <a class="anchor3" href="#"
          >Why We?
          <div class="div3"></div
        ></a>
        <a class="anchor3" href="#"
          >About Us <i class="fa fa-caret-down" aria-hidden="true"></i>
          <div class="div3"></div>
          <div  class="display-content">
            <a href="#">Our Partnerships</a>
          </div></a
        >
        <a class="anchor3" href="#"
          >Blogs
          <div class="div3"></div
        ></a>
  </div>
    </section>
  </header>
</template>
<script>
export default {
  name: "Home",
  data(){
    return {toggle:false}
  },
  methods: {
        myFunction() {
        this.toggle=!this.toggle
},
  }
};
</script>

<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
}
header[class="header"] {
  // width:100%;

  font-family: montserrat, Sans-serif;
  section[class="section1"] {
    //  overflow: auto;
    background-color: maroon;
    //  border : 1px solid yellow;
    display: flex;
    width: 100%;
    height: 60px;
    //   box-sizing: border-box;
    justify-content: space-around;
    align-items: center;
    p[class="p1"] {
      color: white;
      box-sizing: border-box;
      flex: 3;
      // width: 60%;
      height: 30px;
      text-align: center;
      font-size: 15px;
      font-weight: 600;
      //  border : 1px solid red;
      padding-top: 15px;
      //  padding-left: 20px;
      font-family: montserrat, Sans-serif;
    }
    div[class="div1"] {
      box-sizing: border-box;
      color: #0200dd;
      flex: 2;

      a[class="anchor1"] {
        float: left;
        padding-top: 12px;
        padding-bottom: 12px;

        background-color: white;
        text-align: center;
        color: #0200dd;
        overflow: hidden;
        text-decoration: none;
        box-sizing: border-box;
        font-family: montserrat, Sans-serif;
        font-size: 16px;
        font-weight: 500;
        width: 60%;
        height: 45px;
        border-radius: 5px;
        transition: width 5s height 5s;
        transition-timing-function: ease;
      }

      a[class="anchor1"]:hover {
        cursor: pointer;
        width: 70%;
        height: 50px;
        // div[class="div3"] {
        //   display: none;
        //   position: absolute;
        //   background-color: #f9f9f9;
        //   min-width: 160px;
        //   box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
        //   z-index: 1;
        // }
      }
    }
  }

  nav[class="nav2"] {
    //overflow: auto;
    width: 100%;
    height: 50px;
    background-color:black;

    color: white;
    //  border : 1px solid red;
    display: flex;
    box-sizing: border-box;
    justify-content: space-around;
    align-items: center;
    padding-left: 30%;

    p[class="p2"] {
      // margin-top: 20px;
      font-family: "Montserrat", Sans-serif;
      font-size: 14px;
      font-weight: 300;
      text-decoration: none;
      color: white;
      //  border : 1px solid blue;
      // padding-right: 10px;
      // padding-left : 20px;
      text-align: center;
      // i{
      //   border: 1px solid red;
      //   color: brown;
      // }
    }

    a[class="anchor2"] {
      // margin-top: 20px;
      font-family: "Montserrat", Sans-serif;
      font-size: 14px;
      font-weight: 300;
      text-decoration: none;
      color: white;
      text-align: center;
    }
  }

  section[class="section3"] {
    width: 100%;
    height: 90px;
    display: flex;
    flex-direction: row;
    background-color: white;
    img[class="img3"] {
      width: 20%;
      padding: 14px 16px;
    }
    nav[class="nav3"] {
      width: 80%;
      display: flex;
      justify-content: end;
      align-content: space-around;
      padding: 14px 16px;

      a[class="anchor3"] {
        font-family: "Montserrat", Sans-serif;
        font-size: 16px;
        font-weight: 500;
        position: relative;
        //  border:1px solid green;
        //display: inline-block;
        color: black;
        margin-top: 12px;
        margin-right: 30px;
        text-decoration: none;

        div[class="display-content"] {
          display: none;
          position: absolute;
          top: 50px;
          left: 0;
          background-color: #f9f9f9;
          min-width: 160px;
          box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
          z-index: 1;
          a {
            float: none;
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
            text-align: left;
          }
        }
      }

      a[class="anchor3"]:hover {
        div[class="div3"] {
          position: absolute;
          top: 30px;
          left: 0;
          width: 100%;
          height: 3px;
          background-color: blue;
        }
        div[class="display-content"] {
          display: block;
          margin: 0;

          a:hover {
            background-color: #ddd;
            color: black;
          }
        }
      }
    }


    a[class="menu3"] {
      display: none;
      background-color: deepskyblue;
      color: white;
      padding: 10px;
      margin-top: 20px;
      margin-right: 20px;
      position: relative;
    }
    
       div[id="dropdown-content"]{
         display: block !important;
       }

        div[class="dropdown-content"]{
              display: none;
               position: absolute;
               top:90px;
               left:0;
            background-color: #f1f1f1;
           min-width: 70%;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;

               a[class="anchor3"] {
                 color: black;
                 font-family: montserrat,Sans-serif;
                 font-size: 16px;
                 font-weight: 400;
                 padding-top: 25px ;
                 padding-bottom: 25px;
                 padding-left:20%;
                 text-align: left;
                 text-decoration: none;
                display: block;
                  a{
                    display: none;
                  }
                }
                a[class="anchor3"]:hover{
                  background-color: #ddd;
            color: black;
                }
            }

    .show{
      display: block;
      
    }

  }



  @media only screen and (max-width: 1024px) {
    section[class="section1"] {
      display: block;
    
      width: 100%;
      height: 90px;
     p[class="p1"] {
      color: white;
      box-sizing: border-box;
     // flex: 3;
      // width: 60%;
      height: 35px;
      text-align: center;
      font-size: 15px;
      font-weight: 600;
      //  border : 1px solid red;
      padding-top: 15px;
      //  padding-left: 20px;
      font-family: montserrat, Sans-serif;
    }
    div[class="div1"] {
      display: flex;
     // border: 1px solid red;
     // color: #0200dd;
      margin-top: 5px;
      a[class="anchor1"] {
       // float: left;
        padding-top: 12px;
        padding-bottom: 12px;
     margin-left:30%;
        width: 300px;
        height: 35px;
        border-radius: 5px;
        transition: width 5s height 5s;
        transition-timing-function: ease;
      }

      a[class="anchor1"]:hover {
        cursor: pointer;
        width: 320px;
        height: 40px;
       
      }
    }
    }

    nav[class="nav2"] {
      padding-left: 0;
      font-size: 10px;
    }
    section[class="section3"] {
      height: auto;
      position: relative;
      nav[class="nav3"] {
        display: none;
        // border: 1px solid red;
      }

      a[class="menu3"] {
        // flex:6;
        display: block;
        position: absolute;
        top: 0;
        right: 0;

           
      }
      .show{
        display: block;
      }
     
    }
  }

  @media only screen and (max-width: 767px) {
    section[class="section1"] {
      display: flex;
       width: 100%;
      height: 100px;
      flex-direction: column-reverse;

         p[class="p1"] {
      color: white;
      box-sizing: border-box;
      margin-bottom: 5px;
      text-align: center;
      font-size: 12px;
     
     // border : 1px solid red;
     
      font-family: montserrat, Sans-serif;
    }

        div[class="div1"] {
             display: flex;
            // margin-right: 5px;
             margin-top: 10px;
             margin-bottom:5px;
            // padding-bottom: 10px;;
            // border: 1px solid red;
      a[class="anchor1"] {
      margin-top: 5px;
        margin-left:15%;
        width: 300px;
        height: 35px;
     
      }
        }
      a[class="anchor1"]:hover {
        cursor: pointer;
        width: 320px;
        height: 38px;
       
      }
    
    }
     
    nav[class="nav2"] {
      display: none;
    }
  }
  //  @media only screen and (max-width: 440px){
  //       section[class="section1"]{
  //         display: none;
          
        
  //       }
   //   }

}
</style>