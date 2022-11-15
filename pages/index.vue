<template>
  <div>
    <v-img :src="require('../assets/header2.svg')" lazy-load>
    <v-img :src="require('../assets/headermask.svg')" lazy-load>
      <v-img :src="require('../assets/header.png')" lazy-load > 
        <v-container>
      <v-row>
        <v-col cols="12" lg="12">
          <div class=" headerText">
<v-img :src="require('../assets/headerText.svg')"></v-img>
<p class="pararaphFont white--text text-center" >Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been 
the industry's standard dummy text ever since the 1500s,</p>

</div>
        </v-col>
      </v-row>
      </v-container>
  </v-img>
    </v-img>

  </v-img>
  <v-img :src="require('../assets/header3.svg')" class=" pt-0 header2" lazy-load></v-img>
  <div class="d-flex headerGroup justify-space-between">
    <v-img :src="require('../assets/headerGroup (2).svg')" class="headerGroup1" lazy-load></v-img>
  <v-img :src="require('../assets/headerGroup (1).svg')" class="headerGroup2" lazy-load></v-img>
  </div>
  

<v-container fluid >
    <v-row>
      <v-col cols="12" lg="6" class=" pb-0">
        <v-card class="aboutUsText" width="90%" color="transparent" elevation="0">
          <v-card-text>
            <h1 class=" black--text headingFont">About Us</h1>
<p class="mt-10 pararaphFont black--text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.
   Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
    when an unknown printer took a galley of type and scrambled it to make a type 
    specimen book. It has survived not only five centuries, but also the leap into
     electronic typesetting, 

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum 
has been the industry's standard dummy text ever since the 1500s, when an unknown printer 
took a galley of type and scrambled it to </p>
          </v-card-text>
        </v-card>

      </v-col>
      
      <v-col cols="12" lg="6" class=" pb-0" >
        <div style="position:relative; top:200px">
        <div class="box"></div>
        <div class="text-center">
          <img :src="require('../assets/Rectangle 5.svg')" class="image" lazy-load>
        </div>
        <div class="box2"></div>
      </div>
</v-col>
<v-col cols="12" lg="4">
         <v-img :src="require('../assets/Group 124.svg')"  lazy-load></v-img>

</v-col>
       
<v-col cols="12" lg="5">
  <v-card class="expertiseCard" width="100%"  elevation="0">
    <v-card-text>
      <h1 class="headingFont text-center black--text">Expertise</h1>
         <p class="pararaphFont mt-10 text-center black--text">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been </p>
    </v-card-text>
  </v-card>
         

</v-col>
</v-row>

<div style="margin-top:200px">
  <v-img :src="require('../assets/Rectangle 37.svg')"  lazy-load>
    <v-img :src="require('../assets/Rectangle 41.svg')"  lazy-load>
    <div class="d-flex justify-center" style="position:relative">
      <v-img :src="require('../assets/New folder/Rectangle 40.svg')" class="firstImage"  lazy-load></v-img>
      <img :src="require('../assets/New folder/Rectangle 38.svg')" class="secondImage" lazy-load/>
      <v-img :src="require('../assets/New folder/Rectangle 39.svg')" class="thirdImage" lazy-load></v-img>
    </div>
    </v-img>
  </v-img>
  

</div>


<v-row>
<v-col cols="12" lg="6">
  <v-card elevation="0" width="80%" class="capitalCard">
    <v-card-text>
      <h1 class="headingFont black--text">Capital Structure</h1>
  <p class="pararaphFont black--text
 mt-10">Lorem Ipsum is simply dummy text of the printing and typesetting industry.
   Lorem Ipsum has been the industry's 
  standard dummy text ever since the 1500s, when an unknown printer took a galley of type</p>
    </v-card-text>
  </v-card>
  
  
</v-col>
<v-col cols="12" lg="6">
  <div class="d-flex">
    <v-img :src="require('../assets/New folder/Rectangle 7.svg')" class="capitalCardImage1"  lazy-load>
      <div class="pt-16 text-center">
    <h3 class="white--text mt-16">Public Companies </h3>
    
  </div>
  <div  >
    <p class="white--text pararaphFont text-center"> Lorem Ipsum is simply dummy text of <br> the printing and</p>
  </div>
    </v-img>
    <v-img :src="require('../assets/New folder/Rectangle 36.svg')" class="capitalCardImage2"  lazy-load>
      <div class="bottom ">
        <h3 class="white--text ">Academia & Non-Profits </h3>
      </div>
    
    </v-img></div>
    <div class="d-flex">
      <v-img :src="require('../assets/New folder/Rectangle 9.svg')" class="capitalCardImage3"  lazy-load>
        <div class="bottom">
          <h3 class="white--text ml-14">Venture Capital </h3>
        </div>
      
    </v-img>
  <v-img :src="require('../assets/New folder/Rectangle 8.svg')" class="capitalCardImage4 test"  lazy-load>
    <div class="bottom ml-16 pl-16">
      <h3 class="white--text ml-16">Private Equity
</h3>
    </div>
  
  </v-img>
    </div>
  
</v-col>
       
    </v-row>
    <div class="">
      <v-img :src="require('../assets/New folder/people.svg')" class="peopleImage"  lazy-load></v-img>
      <v-img :src="require('../assets/New folder/peoplemask.svg')" class="mb-2 mx-auto peopleDiv"  lazy-load>
            <v-img :src="require('../assets/New folder/peopleimg.svg')" class="mt-3 mx-auto"  lazy-load>
              <v-card width="60%" class="mx-auto peopleCard" color="transparent" elevation="0">
<v-card-text>
  <h1 class=" white--text text-center headingFont">People</h1>
              <p class="white--text text-center pararaphFont mt-10">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been </p>

</v-card-text>
              </v-card>
                            <v-row class="justify-center">
      <v-col cols="12" lg="2">
        <v-img :src="require('../assets/New folder/1 (2).svg')" class="mb-2 mx-auto imageHover" width="250"  lazy-load></v-img>
        <h6 class="text-center pararaphFont white--text mt-2">Scott Blanchette </h6>
        <div class="d-flex justify-center mt-2">
          <img :src="require('../assets/f_1_.svg')"  width="5px" lazy-load/>
          <img :src="require('../assets/insta.svg')" class="ml-5"  width="10px" lazy-load/>
          <img :src="require('../assets/_x30_4.Twitter.svg')" class="ml-5" width="10px" lazy-load/>

          <img :src="require('../assets/linkedin-black 1.svg')" class="ml-5"  width="10px" lazy-load/>
        </div>
      </v-col>
      <v-col cols="12" lg="2"><v-img :src="require('../assets/New folder/1 (3).svg')" class="mb-2 mx-auto imageHover" width="250" lazy-load></v-img>
        <h6 class="text-center pararaphFont white--text mt-2">Norbert Thomas  </h6>
        <div class="d-flex justify-center mt-2">
          <img :src="require('../assets/f_1_.svg')"  width="5px" lazy-load/>
          <img :src="require('../assets/insta.svg')" class="ml-5"  width="10px" lazy-load/>
          <img :src="require('../assets/_x30_4.Twitter.svg')" class="ml-5" width="10px" lazy-load/>

          <img :src="require('../assets/linkedin-black 1.svg')" class="ml-5"  width="10px" lazy-load/>
        </div></v-col>
      <v-col cols="12" lg="2"><v-img :src="require('../assets/New folder/1 (1).svg')" class="mb-2 mx-auto imageHover" width="250" lazy-load></v-img>
        <h6 class="text-center pararaphFont white--text mt-2">Ralph Worthington  </h6>
        <div class="d-flex justify-center mt-2">
          <img :src="require('../assets/f_1_.svg')"  width="5px" lazy-load/>
          <img :src="require('../assets/insta.svg')" class="ml-5"  width="10px" lazy-load/>
          <img :src="require('../assets/_x30_4.Twitter.svg')" class="ml-5" width="10px" lazy-load/>

          <img :src="require('../assets/linkedin-black 1.svg')" class="ml-5"  width="10px" lazy-load/>
        </div></v-col>
    </v-row></v-img>
          </v-img>
     
    </div>
    
    <div>
      <h1 class="text-center headingFont black--text">Industries</h1>
      <p class="text-center pararaphFont black--text">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been </p>
    </div>
    <div class="d-flex justify-center flex-wrap mt-10">
      <v-card width="15%" height="171">

        <v-card-subtitle class="text-center pararaphFont black--text">
          <v-img :src="require('../assets/New folder/Ellipse 5.svg')" class="mb-2 mx-auto" width="60" lazy-load>
            <v-img :src="require('../assets/New folder/Group.svg')" class="mt-3 mx-auto" width="30" lazy-load></v-img>
          </v-img>
         <span class=""> Healthcare </span>
        </v-card-subtitle>
      </v-card>
      <v-card width="15%" height="171" class="ml-10">

<v-card-subtitle class="text-center pararaphFont black--text">
  <v-img :src="require('../assets/New folder/Ellipse 5.svg')" class="mb-2 mx-auto" width="60" lazy-load>
    <v-img :src="require('../assets/New folder/cardimg.svg')" class="mt-3 mx-auto" width="30" lazy-load></v-img>
  </v-img>
  Financial Services  
</v-card-subtitle>
</v-card>
<v-card width="15%" class="ml-10" height="171">

<v-card-subtitle class="text-center pararaphFont black--text" >
  <v-img :src="require('../assets/New folder/Ellipse 5.svg')" class="mb-2 mx-auto" width="60" lazy-load>
    <v-img :src="require('../assets/New folder/cardimg (1).svg')" class="mt-3 mx-auto" width="30" lazy-load></v-img>
  </v-img>
  Federal & State Government  
</v-card-subtitle>
</v-card>
<v-card width="15%" class="ml-10" height="171">

<v-card-subtitle class="text-center pararaphFont black--text">
  <v-img :src="require('../assets/New folder/Ellipse 5.svg')" class="mb-2 mx-auto" width="60" lazy-load>
    <v-img :src="require('../assets/New folder/cardimg (2).svg')" class="mt-3 mx-auto" width="30" lazy-load></v-img>
  </v-img>
  Energy & Resources   
</v-card-subtitle>
</v-card>
<v-card width="15%" class="ml-10" height="171">

<v-card-subtitle class="text-center pararaphFont black--text">
  <v-img :src="require('../assets/New folder/Ellipse 5.svg')" class="mb-2 mx-auto" width="60" lazy-load>
    <v-img :src="require('../assets/New folder/cardimg (3).svg')" class="mt-3 mx-auto" width="30" lazy-load></v-img>
  </v-img>
  Academia  
</v-card-subtitle>
</v-card>
</div>
<div class="d-flex justify-center flex-wrap mt-10">
<v-card width="15%" class="ml-10" height="171">
<v-card-subtitle class="text-center pararaphFont black--text">
  <v-img :src="require('../assets/New folder/Ellipse 5.svg')" class="mb-2 mx-auto" width="60" lazy-load>
    <v-img :src="require('../assets/New folder/cardimg (4).svg')" class="mt-3 mx-auto" width="30" lazy-load></v-img>
  </v-img>
  Technology & 
Telecommunications  
</v-card-subtitle>
</v-card>
<v-card width="15%" class="ml-10" height="171">

<v-card-subtitle class="text-center pararaphFont black--text">
  <v-img :src="require('../assets/New folder/Ellipse 5.svg')" class="mb-2 mx-auto" width="60" lazy-load>
    <v-img :src="require('../assets/New folder/cardimg (5).svg')" class="mt-3 mx-auto" width="30" lazy-load></v-img>
  </v-img>
  Manufacturing, Transport 
& Logistics  
</v-card-subtitle>
</v-card>
<v-card width="15%" class="ml-10" height="171">

<v-card-subtitle class="text-center pararaphFont black--text">
  <v-img :src="require('../assets/New folder/Ellipse 5.svg')" class="mb-2 mx-auto" width="60" lazy-load>
    <v-img :src="require('../assets/New folder/cardimg (6).svg')" class="mt-3 mx-auto" width="30" lazy-load></v-img>
  </v-img>
  Venture Capital & Private 
Equity  
</v-card-subtitle>
</v-card>
    </div>
    <div class="d-flex footerGroup justify-space-between">
    <v-img :src="require('../assets/New folder/footerVector (1).svg')" class="footerGroup1" lazy-load></v-img>
  <v-img :src="require('../assets/New folder/footerVector (2).svg')" class="footerGroup2" lazy-load></v-img>
  </div>
    </v-container>
    <div class="footerImage">
    <v-img :src="require('../assets/New folder/footer mask.svg')" class="" lazy-load>
      <v-img :src="require('../assets/New folder/footer img.svg')" class="" lazy-load>
        <v-container>
        <v-row class="justify-space-between">
          <v-col cols="12" lg="5">
            <h1 class="contactUs white--text headingFont">Contact Us</h1>
            <p class="white--text pararaphFont">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been </p>
          <v-row>
            <v-col cols="12" lg="6">
              <div class="d-flex">
                <img :src="require('../assets/New folder/Frame 38.svg')" alt="">
                <h4 class="label">First Name</h4>
              </div>
<input type="text" placeholder=""/>
            </v-col>
            <v-col cols="12" lg="6">
              <div class="d-flex">
                <img :src="require('../assets/New folder/Frame 38.svg')" alt="">
                <h4 class="label">Last Name</h4>
              </div>
              <input type="text" placeholder=""/>
            </v-col>
            <v-col cols="12" lg="12">
              <div class="d-flex">
                <img :src="require('../assets/mail.svg')" alt="">
                <h4 class="label">Email</h4>
              </div>
              <input type="text" placeholder=""/>
            </v-col>
            <v-col cols="12" lg="12">
              <div class="d-flex">
                <img :src="require('../assets/mail.svg')" alt="">
                <h4 class="label">Message</h4>
              </div>
              <input type="text" placeholder="" style="padding-top:200px"/>
            </v-col>
          </v-row>
          <v-btn class="text-capitalize  mt-16" color="white" tile>Contact us</v-btn>
          
          </v-col>
          <v-col cols="12" lg="5">
            <h2 class="contactUs white--text headingFont">Office Locations</h2>
            <v-list color="transparent">
              <v-list-item>
                <v-list-item-icon>
                  <v-img :src="require('../assets/New folder/location icon.svg')" class="" lazy-load></v-img>
                </v-list-item-icon>
                <v-list-item-title class="white--text pararaphFont">Nashville Office 
10 Burton Hills Blvd
Nashville, TN 37215</v-list-item-title>
              </v-list-item>
              <v-list-item>
                <v-list-item-icon>
                  <v-img :src="require('../assets/New folder/location icon.svg')" class="" lazy-load></v-img>
                </v-list-item-icon>
                <v-list-item-title class="white--text pararaphFont">Washington, DC Office 
1875 K St NW
Washington, DC 20006</v-list-item-title>
              </v-list-item>
              <v-list-item>
                <v-list-item-icon>
                  <v-img :src="require('../assets/New folder/location icon.svg')" class="" lazy-load></v-img>
                </v-list-item-icon>
                <v-list-item-title class="white--text pararaphFont">Quebec City, Canada Office 
2828 Bd Laurier
Québec, QC G1V 0B9, Canada
</v-list-item-title>
              </v-list-item>
            </v-list>
          </v-col>
        </v-row>
      </v-container>
    </v-img>
    </v-img>
  </div>
  </div>
</template>

<script>
import lazyLoad from 'vue-lazyload'
import "vue-slick-carousel/dist/vue-slick-carousel.css";
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";
export default {
  target: 'static',
  components: { lazyLoad },
  name: 'IndexPage',
  data (){
    return {
    }
  }
}
</script>
<style scoped>
.bottom{
  display:flex;
  flex-direction: column;
  justify-content: flex-end;
  height: 350px;
  margin-left:50px
}
h3{
  font-family:'Raleway';
  font-size:25px;
  font-weight:700;
}
.contactUs{
  margin-top:250px;
}
.header2{
  margin-top:-150px
}
.headerGroup{
  margin-top:-1080px;
  /* position: absolute; */
  /* top:300px */

}

input {
    color: #ffffff !important;
    border-bottom: 1px dotted white;
    width:100%;
    padding-top:10px;
    /* margin-top:50px; */
}

.footerGroup{
  margin-top:-900px;
}
.footerGroup1{
margin-right: 300px;
}
.footerGroup2{
margin-left: 300px;
}
.headerGroup1{
margin-right: 400px;
}
.headerGroup2{
margin-left: 400px;
}
.label{
  font-family: 'Raleway';
  font-size: 16px;
  font-weight: 500;
  color:white;
  margin-left:20px;
  margin-top:10px

}
.headerText{
position: absolute;
top: 400px;
left:400px;
width:1039px
}
.box{
  width: 290px;
height: 244px;
position:absolute;
left: 15%;
top: -10px;
background: linear-gradient(125.28deg, #0EA1EF 0%, #064BCA 100%);
opacity: 0.2;
border-radius: 20px;
/* z-index: -1; */
}
.box2{
  width: 290px;
height: 244px;
position:relative;
left: 54%;
bottom: 230px;
background: linear-gradient(125.28deg, #0EA1EF 0%, #064BCA 100%);
opacity: 0.2;
border-radius: 20px;
/* z-index:10; */
}
.image{
  width: 603px;
height: 619px;
text-align: center;
}
.aboutUsText{
  margin-top: 350px;
  font-family:'Raleway'
}
.expertiseCard{
  margin-top: 180px;
}
.headingFont{
  font-weight: 700;
  font-size: 60px;
  font-family:'Raleway';
}
.pararaphFont{
  font-family: 'Raleway';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 35px;
/* or 175% */

text-align: left;

color: #000000;

opacity: 0.8;
}
@font-face {
  font-family: "Raleway";
  src:    url(../assets/font/Raleway-Regular.ttf) }
  .borderred{
    border:1px solid red
  }
  .bordergreen{
    border:1px solid green
  }
  .firstImage{
    width:500px;
    height:500px;
    z-index: 100;
    position:absolute;
left:150px;
margin-top:-100px
  }
  
 
  .secondImage{
    width:900px;
    height:900px;
    position:absolute;
    left:450px;
    /* top:10px; */
    /* bottom: 60px; */
    margin-top:-300px;
    z-index: 15000;
  }
  .thirdImage{
    margin-top:-100px;
    width:500px;
    height:500px;
    position:absolute;
    z-index: 100;
    left:1150px
  }
  .capitalCard{
    margin-top: 350px;
  }
  .capitalCardImage1{
width:'50%';
height:'20%';
margin-top:80px;
  }
  .imageHover{
border-style: none;
  }
  .imageHover:hover{
    background: linear-gradient(0deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5));
mix-blend-mode: normal;
  }
  .capitalCardImage1:hover {
    background: linear-gradient(0deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5));
    mix-blend-mode: luminosity;
    border-radius:20px;
}
.capitalCardImage2:hover {
    background: linear-gradient(0deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5));
    mix-blend-mode: luminosity;
    border-radius:20px;
}
.capitalCardImage3:hover {
    background: linear-gradient(0deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5));
    mix-blend-mode: luminosity;
    border-radius:20px;
}
.capitalCardImage4:hover {
    background: linear-gradient(0deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5));
    mix-blend-mode: luminosity;
    border-radius:20px;
}
  .capitalCardImage2{
width:'10%';
height:'20%';
margin-top:80px;
margin-left:20px;
  }
  .capitalCardImage3{
width:'10%';
height:'20%';
margin-top:20px;
  }
  .capitalCardImage4{
width:'10%';
height:'20%';
margin-top:20px;
margin-left:20px;
  }
  .peopleImage{
    margin-top:-550px
  }
  .peopleDiv{
    position:relative;
    bottom:330px
  }
  .peopleCard{
    margin-top:300px
  }
  .footerImage{
    margin-top:-100px
  }
</style>
