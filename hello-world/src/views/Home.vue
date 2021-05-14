<style scoped>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* .container{
  background-color: black;
} */
.img{
  background-color: black;
  color: red;  
  height: 200px; 
  min-width: 500px;
  font-size:20px;
  justify-content: flex-start;
}
.img2{
  display: flex;
  /* background-color:pink; */
  min-width: 140%;
  margin-top: 35%;
  margin-left: 40%;
}
@media only screen and (min-width:300px) {
.text{
 
   margin-top: -12%; 
   }

}
.text1{
   font-size:30px;
   /* background-color: rgb(13, 255, 85); */
   width: 100%;
   height: 60%;
   margin-bottom:80%;
   margin-top: -205%; 
   margin-left: 50%;

}

.text_color{
font-size:30px;
color: #00aeff;
display: flex;
/* justify-content: flex-start; */
/* background-color: black; */
max-width: 30%;
margin-left: 105%;
margin-top:-17.5% ;
}
.text_color2{
font-size:30px;
color: #00aeff;
display: flex;
/* background-color: black; */
justify-content: flex-end;
margin-top: -6%;
margin-right:38%;
}

.text2{
 
  font-size: 100%;
  height: 30%;

}

.text3{
  /* background-color: rgb(81, 245, 122); */
  margin-top: 5%;
}
.box{
  /* background-color: rgb(81, 245, 122);  */
  width: 20%;
  margin-top: -5%;
  margin-left: 14%;
  
}
.icon{
  justify-content: flex-end;
  background-color: rgb(98, 0, 255); 
  margin-left: 22%;
  margin-top: -5%;
}
.link{
 
   background-color: rgb(98, 0, 255); 
   width: 12%;
   margin-left: 30%;
   margin-top: -3.7%;
  /* ย้ายกล่อง */
}
.link2{
  background-color: rgb(0, 119, 255); 
   width:8%;
   margin-left: 50%;
   margin-top: -3.9%;
}
.icon2{
  color: #00aeff;
}
.box2{
  margin-left: 28%;
  margin-top: -105%;
}
.box3{
 
  width: 135%;
  margin-top: -125%;
  margin-left: 40%;
}
.box4{
   width: 135%;
  margin-top: -125%;
  margin-left: 55%;
}
 .box5{
  background-color: bisque; 
  width: 65%;
  margin-top: -115%;
  margin-left: 40%;
} 

</style>
<template >
  <v-container >
    <v-row>
      <v-col cols="6" sm="12" md="6" lg="6" xl="12">
        <v-row>
          <div class="text"> 
           <h1 class="text1">Seriously Powerful  
           <p class="text_color  ">Career</p>
           <p class="text_color2">Preparation</p> 
         </h1> 
          </div>
        </v-row>
        <v-row>
          <div class="box2">
          <h1 class="text2">Work with Upkey to prepare yourself for the professional world! We've helped transform tens of thousands of students into standout applicants thanks to custom support, opportunities, and guidance that can only be found at Upkey.</h1>
          </div>
        </v-row>
        <v-row>
          <v-col cols="6">
            <div class="box4">
            <v-btn 
          height="45" 
          color="rgba(0, 174, 255)"
          class="white--text  "
           > start Today ! </v-btn> 
           </div>
          </v-col>
          <v-col cols="6">
            <div class="box5">
             <a 
             href="#" 
             class="text-decoration-none"
             >Explore internships</a>
            </div>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="12" sm="12" md="6" lg="6" xl="6">
        <div class="box3">
        <v-img :src="require('../assets/upkey.png')"
       />
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>
