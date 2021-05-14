

<template>
  <!-- fluid  -->

  <!-- page1 -->
  <v-container fluid>
    <div class="bg">
      <v-row class="test">
        <v-col cols="12" xs="12" md="6" lg="6">
        
          
          <v-row>
            <v-col>
              <div class="one">
              <div class="text">
            <h1>
              Seriously Powerful
              <span class="text_color">Career</span>
              <div class="text_color">Preparation</div>
            </h1>
          </div>
              <div class="content_page1">
                <p>
                  Work with Upkey to prepare yourself for the professional
                  world! We've helped transform tens of thousands of students
                  into standout applicants thanks to custom support,
                  opportunities, and guidance that can only be found at Upkey.
                </p>
                <br />
                <p>
                  We are proud to offer students access to Upkey free of charge.
                </p>
              </div>
              <v-btn height="4.5rem" width="11rem" color="rgba(0, 174, 255)" class="btn">
                Start today!
              </v-btn>
               <p class="link">Explore Internship</p>
              <v-img
                class="arrow"
                max-width="14px"
                :src="require('../assets/arrow-right (1).png')"
              />
              </div>
            </v-col>
            
          </v-row>
        </v-col>



        <v-col cols="12" xs="12" md="6" lg="6">
          <div class="img1">
            <v-img
              max-width="620"
              src="https://upkey.com/images/pages/home-hero-image.svg"
            />
          </div>
          
        </v-col>
      </v-row>

      <!-- page2 -->

      <v-row class="content">
        <!-- img1 -->
        
        <v-col cols="12" xs="12" md="12" lg="12">
          <div class="img_page2">
            <h1 class="head">
              
              <b>Stand Out in a Crowd of Applicants</b>
              
            </h1>
            <div class="size_ing1">
              <v-img
                src="https://upkey.com/images/pages/home-we-learn-about-you.svg"
              />
            </div>
            <p class="page21">
              <v-card-title class="titlt1">We Learn About You</v-card-title>
              We identify where you are in your career journey and learn about
              your strengths and goals. Once we know the things that make you,
              we’ll have a better understanding of how to help you stand out
              from other job applicants.
            </p>
          </div>
        </v-col>

        <!-- img2 -->

        <v-col cols="12" xs="12" md="12" lg="12">
          <div class="img1_page2">
            <div class="size_ing2">
              <v-img
                src="https://upkey.com/images/pages/home-we-build-for-you.svg"
              />
            </div>
            <div class="page0002">
              <p>
                <v-card-title class="titlt1">We Build For You</v-card-title>
                We build you a custom dashboard that includes a map laying out a
                step-by-step path toward your future. You’ll never wonder what
                you should do next as you progress toward your professional
                goals.
              </p>
            </div>
          </div>
        </v-col>

        <!-- img3 -->

        <v-col cols="12" xs="12" md="12" lg="12">
          <div class="img2_page2">
            <div class="size_ing3">
              <v-img
                src="https://upkey.com/images/pages/home-you-take-charge-of-your-future.svg"
              />
            </div>
            <!-- <p class="page23"> -->

            <div class="page0003">
              <v-card-title class="titlt33"
                >You Take Charge of Your Future</v-card-title
              >
              <p class="page222">
                We build you a custom dashboard that includes a map laying out a
                step-by-step path toward your future. You’ll never wonder what
                you should do next as you progress toward your professional
                goals.
              </p>
            </div>
          </div>
        </v-col>
      </v-row>

      <!-- Page3 -->

      <v-row class="content1">
        <v-col cols="12" xs="12" md="6" lg="6">
          <div class="text3">
            <div class="Control">
              <h2>
                <b>
                  Take Control of Your
                  <span class="text_color"> Prossfessional Journey</span>
                </b>
              </h2>
            </div>
            <div class="animath">
              <v-img :src="require('../assets/qww.png')" width="35rem" />
            </div>
            <p class="page3_1">
              As you develop your career skills and personal brand, you will
              earn badges to boost your professional rank. The higher rank you
              are, the more opportunities and experiences you'll unlock.
            </p>

            <v-btn class="btn3" height="4rem" width="8rem" color="#00AEFF"> try it out! </v-btn>
          </div>
        </v-col>
      </v-row>

      <!-- Page4 -->
       <v-row class="content2"> 
        <v-col cols="12" xs="12" md="6" lg="6">
          
          <div class="img_page3">
            <v-img
              src="https://upkey.com/images/pages/home-dashboard-photo.png"
            />
          </div>
          
          <div class="text3_page3">
            <h2>
              Your Upkey Dashboard: Customized to
              <span class="text_color"> Your Career Goals</span>
              <p class="content_page31">
                Your personalized Upkey Dashboard is home to a ton of helpful
                tools you can use to construct a solid professional foundation
                upon which to build your future, including:
              </p>
            </h2>
            <ul>
              <li>
                <v-img
                  class="img77"
                  max-width="40px"
                  src="https://upkey.com/images/icons/speaker.svg"
                />
                <h1 class="icon_text1">
                  Live virtual programs hosted by industry leaders
                </h1>
              </li>
              <li>
                <v-img
                  class="img77"
                  max-width="40px"
                  src="https://upkey.com/images/icons/star.svg"
                />
                <h1 class="icon_text1">
                  Exclusive access to projects, internships, and jobs
                </h1>
              </li>
              <li>
                <v-img
                  class="img77"
                  max-width="40px"
                  src="https://upkey.com/images/icons/technics.svg"
                />
                <h1 class="icon_text1">Career Preparation services</h1>
              </li>
              <li>
                <v-img
                  class="img77"
                  max-width="40px"
                  src="https://upkey.com/images/icons/ecology.svg"
                />
                <h1 class="icon_text1">
                  Badges and certificates to unlock extra career opportunities
                </h1>
              </li>
            </ul>
          </div>
        </v-col>
      </v-row> 

      <!-- Page5 -->
       <v-row class="content5"> 
        <v-col cols="12" xs="12" md="6" lg="6">
          <div class="whatwe">
            <h2>
              What we offer

              <p class="whatwe1">
                Learn more about the tools and programs we offer.
              </p>
            </h2>
          </div>
          <div class="div-img1">
            <div class="div-img11">
              <v-card class="card">
                <v-img
                  :src="require('../assets/qqq.png')"
                  height="200px"
                  width="850px"
                ></v-img>

                <v-card-title> Caree Tools </v-card-title>

                <v-card-subtitle>
                  Resume bulider,oich coach interview prep and more!
                </v-card-subtitle>
              </v-card>
            </div>

            <v-card class="card1">
              <v-img
                :src="require('../assets/zxc.png')"
                height="200px"
                width="850px"
              ></v-img>

              <v-card-title> Caree Tools </v-card-title>

              <v-card-subtitle>
                Resume bulider,oich coach interview prep and more!
              </v-card-subtitle>
            </v-card>
          </div>
        </v-col>
      </v-row> 

      <!-- Page6 -->
       <v-row class="content6"> 
        <v-col cols="12" xs="12" md="6" lg="6">
          <div class="text6">
            <h2 class="text_color">
              <b>96%</b>

              <span class="black"><b> Student satisfaction</b></span>

              <p class="black1">
                For proof of our stellar career-building program, look no
                further than our former
                <span class="black00"> students. </span>
              </p>
            </h2>
          </div>

          <ul class="qq">
            <li class="bx">
              <v-img
                max-width="250px"
                src="https://upkey.com/images/testimonial-slider/LilyOfori-Amanfo.png"
              />
              <h1 class="text_last">
                My experience with Upkey has been life-changing. They see me as
                a student and get what I am going through. I feel so much more
                confident about who I am.
              </h1>
              <h1 class="text_last1"><b>Lily Ofori-Amanfo</b></h1>
              <h1 class="text_last1">
                Bachelor's degree, Management Information Systems, Ashesi
                University
              </h1>
            </li>

            <li class="boxx">
              <v-img
                class="slid"
                max-width="250px"
                src="https://upkey.com/images/testimonial-slider/LucyCai.png"
              />
              <h1 class="text_last">
                My experience with Upkey has been life-changing. They see me as
                a student and get what I am going through. I feel so much more
                confident about who I am.
              </h1>
              <h1 class="text_last1"><b>Lily Ofori-Amanfo</b></h1>
              <h1 class="text_last1">
                Bachelor's degree, Management Information Systems, Ashesi
                University
              </h1>
            </li>

            <li class="boxx1">
              <v-img
                class="slid"
                max-width="250px"
                src="https://upkey.com/images/testimonial-slider/DareenChristabel.png"
              />
              <h1 class="text_last">
                My experience with Upkey has been life-changing. They see me as
                a student and get what I am going through. I feel so much more
                confident about who I am.
              </h1>
              <h1 class="text_last1"><b>Lily Ofori-Amanfo</b></h1>
              <h1 class="text_last1">
                Bachelor's degree, Management Information Systems, Ashesi
                University
              </h1>
            </li>

            <li class="boxx2">
              <v-img
                class="slid"
                max-width="250px"
                src="https://upkey.com/images/testimonial-slider/AnibabaAyodeji.png"
              />
              <h1 class="text_last">
                My experience with Upkey has been life-changing. They see me as
                a student and get what I am going through. I feel so much more
                confident about who I am.
              </h1>
              <h1 class="text_last1"><b>Lily Ofori-Amanfo</b></h1>
              <h1 class="text_last1">
                Bachelor's degree, Management Information Systems, Ashesi
                University
              </h1>
            </li>
          </ul>
        </v-col>
      </v-row> 

      <!-- Page7-->
       <v-row class="content7"> 
        <v-col cols="12" xs="12" md="6" lg="6">
          <div class="text31">
            <h2 class="text_color">
              <b>62 Partners</b>

              <span class="black"> <b> and Counting</b></span>
</h2>
</div>
<div class="move">


              <p class="black4">
                We're proud to partner with incredible schools across the nation
                and help their students transform into
              </p>
              <p class="black3">polished professionals.</p>
            </div>
          

          <div class="logo">
            <v-img class="img000"
              max-width="150px"
              src="https://upkey.com/images/universities/baylor.png"
            />
            <v-img
              class="img00"
              max-width="150px"
              src="https://upkey.com/images/universities/concordia.png"
            />
            <v-img
              class="img10"
              max-width="150px"
              src="https://upkey.com/images/universities/depaul.png"
            />
            <v-img
              class="img11"
              max-width="150px"
              src="https://upkey.com/images/universities/iit.png"
            />
            <v-img
              class="img12"
              max-width="150px"
              src="https://upkey.com/images/universities/loyola.png"
            />
            <v-img
              class="img13"
              max-width="150px"
              src="https://upkey.com/images/universities/purdue.png"
            />
            <v-img
              class="img14"
              max-width="70px"
              src="https://upkey.com/images/universities/uic.png"
            />
            <v-img
              class="img15"
              max-width="150px"
              src="https://upkey.com/images/universities/ucf.png"
            />
            <v-img
              class="img16"
              max-width="150px"
              src="https://upkey.com/images/universities/roosevelt.png"
            />
            <v-img
              class="img17"
              max-width="150px"
              src="https://upkey.com/images/universities/stxavier.png"
            />
          </div>
        </v-col>
      </v-row> 

      <!-- Page8-->

      <v-row class="content8"> 
        <v-col cols="12" xs="12" md="6" lg="6">
          <div class="text310">
            <h2 class="black">
              <b>Get your free</b>
              <span class="text_color"><b> personalized dashboard</b></span>
            </h2>
            <p class="black001">
              Your dashboard includes everything you'll need to tackle the
              professional world! Take classes, revamp your resume, learn new
              skills, and keep track of your career journey.
            </p>
          </div>

          <v-btn class="btn4" color="#00AEFF" width="7rem" height="4rem"> Let's go! </v-btn>
        </v-col>
      </v-row> 

      <!-- Page9 footter-->

       <v-row class="content9"> 
        <v-col cols="12" xs="12" md="6" lg="6">
          <div class="cvb">
            <v-img
              class="img100"
              max-width="40px"
              src="https://upkey.com/images/icons/laurel-icon.svg"
            />
            <h1 class="footer1"><b>#24 LinkedIn Top Startup for 2020</b></h1>

            <div class="vl"></div>
            <p class="linkfooter">Read full article</p>
            <v-img
              class="arrow2"
              max-width="14px"
              :src="require('../assets/arrow-right (1).png')"
            />
          </div>
        </v-col>
      </v-row>

      <!-- Page10 footter -->
    <v-row class="content10"> 
        <v-col cols="12" xs="12" md="6" lg="6">
          <v-img
            class="arrow3"
            width="300px"
            src="https://upkey.com/images/icons/logo.svg"
          />
          <div class="content_page123">
            <p>
              Upkey works with your institution so that you can give your
              students everything they need to succeed in today’s competitive
              job market.
            </p>
          </div>
          <div class="content_page1234">
            <p>
              hello@upkey.com
              <br />
              <br />
              113 W. Hubbard St. Suite 300 Chicago, IL 60654
            </p>
          </div>
          <div class="img_footerdiv">
          <v-img
          class="img_footer1"
          max-width="45px"
          src="https://upkey.com/images/icons/facebook-icon.svg"/>
          <v-img
          class="img_footer2"
          max-width="45px"
          src="https://upkey.com/images/icons/instagram-icon.svg"/>
          <v-img
          class="img_footer3"
          max-width="45px"
          src="https://upkey.com/images/icons/twitter-icon.svg"/>
           <v-img
           class="img_footer4"
          max-width="45px"
         src="https://upkey.com/images/icons/ln-icon.svg"/>

          </div>
          <div class="footerend">
          <p>Tools</p>
          <br>
          <p >Programs</p>
          <br>
          <p >Mentors</p>
          <br>
          <p >Sponsors</p>
          <br>
          <p >Terms</p>
          <br>
          <p >Privacy</p>
          </div>     
          <hr class="solid">
          <p class="end">© Copyright 2020 Upkey LLC. All rights reserved.</p>
        </v-col>
        
      </v-row> 
    </div>

  </v-container>
</template>


<script>
export default {
  name: "Home",
};
</script>
<style scoped>
.container {
  height: 10vh;
  /* background-color: black; */
  width: 100%;
}
.text_color {
  color: #00aeff;
}
.test {
  /* background: red; */
  height: 35rem;
}
.test1 {
  background: red;
  height: 26rem;
}
.content {
  background: linear-gradient(to bottom, #e8f6ff, #ffffff, #ffffff);
  height:110rem;
  width: 150rem;
}
.content1 {
  background: linear-gradient(to bottom, #e8f6ff, #ffffff, #ffffff);
  height: 55rem;
  width: 150rem;
 
}
.content2 {
  background: linear-gradient(to bottom, #ffffff, #ffffff);
  height: 40rem;
  width: 150rem;
}
.content5 {
  /* background: linear-gradient(to bottom, #09ff99, #ffffff); */
  height: 40rem;
  width: 150rem;
}
.content6 {
  /* background: linear-gradient(to bottom, #f11313, #ffffff); */
  height: 62rem;
  width: 150rem;
}
.content7 {
  background: (to bottom, #8c11ff, #ffffff);
  height: 27rem;
  width: 150rem;
}
.content8 {
  background: #e8f6ff;
  height: 20rem;
  width: 150rem;
}
.content9 {
  background: #fff6d9;
  height: 4rem;
  width: 150rem;
}
.content10 {
  background: #ffffff;
  width: 150rem;
  height: 32rem;
}
.img100 {
  margin-top: -2.8rem;
  margin-left: 20rem;
}
.cvb {
  margin-top: 2.6rem;
  margin-left: 11rem;
}
.footer1 {
  margin-left: 23.5rem;
  margin-top: -1.8rem;

  width: 25rem;
  font-family: Nunito, sans-serif;
  font-weight: 600;
  font-size: 17.5px;
}
.vl {
  border-left: 1px solid rgb(0, 0, 0);
  height: 25px;

  margin-left: 44.5rem;
  margin-top: -1.4rem;
}
.page21 {
  /* margin-right: -90%; */
  width: 30%;
  /* background-color: rgb(105, 0, 224); */
  margin-left: 50rem;
  margin-top: -20rem;
  font-family: Nunito, sans-serif;
  font-weight:bold;
  font-size: 18.5px;
}
.page222 {
  /* margin-right: -90%; */
  width: 25rem;
  /* background-color: rgb(105, 0, 224); */
  margin-left: 765px;
  margin-top: -180px;
  font-family: Nunito, sans-serif;
  font-weight: 600;
  font-size: 18.5px;
}
.page3_1 {
  /* margin-right: -90%; */
  width: 35rem;
  /* background-color: rgb(105, 0, 224); */
  /* margin-left: 765px;
  margin-top: -180px; */
  margin-top: -25.8rem;
  margin-left: 52rem;
  font-family: Nunito, sans-serif;
  font-weight: 600;
  font-size: 17.5px;
}
.animath {
  margin-left: 9rem;
  margin-top: 5rem;
}
.Control {
  margin-left: 25.5rem;
  font-size: 22.5px;
  width: 80rem;
}
.head {
  font-weight: 400;
  font-size:33px;
  font-family: Nunito, sans-serif;
  margin-top: 4%;
  margin-left: 26%;
   font-weight: 400;
}
.page0002 {
  width: 30rem;
  /* background-color: rgb(105, 0, 224); */
  margin-left: -2rem;
  margin-top: -15rem;
  font-size: 18.5px;
  font-family: Nunito, sans-serif;
  font-weight: 600;
}
.page23 {
  /* margin-right: -60%; */
  /* background-color: rgb(219, 188, 48); */
  width: 17rem;
  font-size: 13.5px;
  font-family: Nunito, sans-serif;
  margin-left: 600px;
  margin-top: -241px;
}
.box {
  justify-content: center;
}
.one{
  margin-top:5rem ;
  margin-left: 11%;
}
.content_page1 {
  
  margin-top: 20px;
  width: 90%;
  font-family: Nunito, sans-serif;
  font-size: 17.5px;
  font-weight: 600;
  line-height: 1.5;
  color: #222;
  margin-left: 65px;
}
.content_page123 {
  /* background-color: blue; */
  margin-top: 50px;
  width: 30%;
  font-family: Nunito, sans-serif;
  font-size: 18.5px;
  font-weight: 400;
  line-height: 1.5;
  color: rgb(206, 206, 206);
  margin-left: 65px;
}
.img_footer1 {
  margin-top: 10rem;
  margin-left: 3rem;
}
.img_footer2 {
  margin-top: -2.8rem;
  margin-left: 6rem;
}
.img_footer3 {
  margin-top: -2.8rem;
  margin-left: 9rem;
}
.img_footer4 {
  margin-top: -3rem;
  margin-left: 12rem;
}
.img_footerdiv {
  /* margin-left: 22rem;
  margin-top: -8rem; */
  margin-left: 30.999rem;

  margin-top: -8rem;
  width: 15rem;
}
.content_page1234 {
  /* background-color: blue; */
  margin-top: -220px;
  width: 45%;
  font-family: Nunito, sans-serif;
  font-size: 15.5px;
  font-weight: 400;
  line-height: 1.5;
  color: rgb(105, 102, 102);
  margin-left:35rem;
}
.text {
  /* background-color: chartreuse; */
  margin-left: 65px;
  font-family:  sans-serif;
  margin-top: 30px;
  font-weight: 800rem;
  font-size: 20px;
}
.img1 {
  margin-top: 100px;

  margin-left: 20px;
}
.btn {
  margin-left: 65px;
  margin-top: 3rem;
  font-family: Nunito, sans-serif;
  font-weight: 400;
  text-transform: none;
  color: white !important;
  font-size: 18px;
}
.arrow {
  margin-left: 420px;
  width: 100%;
  margin-top: -15.8px;
}
.arrow2 {
  /* background-color: rgb(98, 0, 255); */
  width: 12rem;
  margin-left: 835px;
  margin-top: -1rem;
}
.arrow3 {
  /* background-color: rgb(98, 0, 255); */
  width: 12rem;
  margin-left: 4rem;
  margin-top: 2rem;
}
.link {
  /*background-color: cyan;*/
  margin-top: -40px;
  font-size: 17px;
  margin-left: 260px;
  width: 100%;
  font-weight: bold;
  color: rgb(87, 195, 245);
  font-family: Nunito, sans-serif;
}
.linkfooter {
  /* background-color: rgb(97, 11, 255); */
  margin-top: -20.5px;
  width: 20%;
  font-size: 15px;
  margin-left: 45rem;
  font-weight: bold;
  color: rgb(87, 195, 245);
  font-family: Nunito, sans-serif;
}
hr.solid {
  border-top: 1px solid rgb(233, 233, 233);
  margin-top: 9rem;
  margin-left: -1rem;
  width: 100rem;
}
.end {
  font-size: 13px;
  color: rgb(192, 185, 185);
  margin-top: 2rem;
  width: 100rem;
  margin-left: 38rem;
}
.footerend {
  margin-top: -12rem;
  width: 20%;
  font-size: 15px;
  margin-left: 63rem;
  font-weight: bold;
  color: rgb(87, 195, 245);
  font-family: Nunito, sans-serif;
}
/* line */
/* page2 */
.new4 {
  border: 1px solid rgb(87, 195, 245);
  width: 40px;
  border-radius: 3px;
  background-color: black;
  margin-left: 500px;
  margin-top: 50px;
}
.new5 {
  border: 1px solid rgb(87, 195, 245);
  width: 40px;
  border-radius: 3px;
  background-color: black;
  margin-left: 183px;
  margin-top: 20px;
}
.text1 {
  width: 120%;
  height: 105px;
  margin-left: 340px;
  margin-top: 50px;
  font-family: Nunito, sans-serif;
  font-size: 24px;
  font-weight: bold;
}
.img_page2 {
  width: 96rem;
  height: 40rem;
  margin-left: 9rem;
  margin-top: -20px;
  /* background-color: brown; */
}
.size_ing1 {
  width: 32rem;
  margin-top: 7rem;
  margin-left: 5%;
}
.size_ing2 {
  width: 32rem;
  margin-top: -10rem;
  margin-left: 33rem;
}
.size_ing3 {
  width: 32rem;
  margin-top: -10rem;
  margin-left: 46rem;
}
.img1_page2 {
  width: 300rem;
  height: 15rem;
  margin-left:13rem;
  /* background-color: chartreuse; */
  margin-top: 10rem;
}

.img2_page2 {
  margin-left: -30.6rem;
  margin-top: 25rem;
  width: 900rem;
  height: 30rem;
}
.img_page3 {
  width: 560px;
  background-color: darkviolet;
  margin-left: 50rem;
  margin-top: -9rem;
}

.titlt1 {
  font-weight: 600;
  font-size: 35px;
  margin-left: -16px;
  
  font-family: sans-serif;
  width: 100rem;
}
.titlt33 {
  font-weight:600;
  font-size: 35px;
  margin-left: 46.5rem;
  margin-bottom: 11rem;
  font-family: sans-serif;
  width: 23rem;
}
.cc {
  margin-top: -13rem;
}
.page0003 {
  margin-top: -17rem;
  margin-left: 40rem;
  font-size: 100.5px;
   font-family: sans-serif;
   font-weight:600;

}

.text3 {
  /* background-color: brown; */
  width: 60rem;

  font-family: Nunito, sans-serif;
  font-size: 18px;
  font-weight: bold;
  height: 30rem;
  margin-top: 4rem;
  margin-left: 1rem;
}
.text6 {
  /* background-color: brown; */
  width: 60rem;
  font-family: Nunito, sans-serif;
  font-size: 26px;
  font-weight: bold;
  height: 30rem;
  margin-top: 1rem;
  margin-left: 30rem;
}
/* page3 */
.content-page3 {
  /* background-color: cornflowerblue; */
  font-family: Nunito, sans-serif;
  font-weight: bold;
  font-size: 11px;
  width: 342px;
  margin-left: 35rem;
}
.btn3 {
  color: white !important;
  text-transform: none;
  margin-left: 52rem;
  margin-top: 2rem;
}
.btn4 {
  color: white !important;
  text-transform: none;
  margin-left: 42rem;
  margin-top: -3rem;
  font-size: 16px;
  font-family: Nunito, sans-serif;
}

.text3_page3 {
  width: 35rem;
  font-family: Nunito, sans-serif;
  font-size:26px;
  font-weight: bold;
  height: 160px;
  margin-top: -42rem;
  margin-left: 8rem;
  /* background-color: crimson; */
}
.content_page31 {
  font-size: 18px;
  margin-top: 1rem;
  
}
.icon_text1 {
  font-size: 18px;
  margin-left: 3.5rem;
  margin-top: -25px;
  /* background-color: crimson; */
  width: 30rem;
  font-family: Nunito, sans-serif;
}
.img77 {
  margin-left: -1px;
  margin-top: 2rem;
  /* background-color: darkblue; */
}
ul {
  list-style-type: none;
}
.whatwe {
  margin-top: 4rem;
  margin-left: 38.5rem;
  width: 90%;
  font-family: Nunito, sans-serif;
  font-size: 26px;
  /* background-color: darkblue; */
}
.whatwe1 {
  font-size: 15px;
  margin-top: 1rem;
  margin-left: -6%;
  font-family: Nunito, sans-serif;
}
.card {
  width: 34rem;
  height: 18rem;
  margin-left: -20rem;
  elevation: 20px;

  /* margin-bottom: -20rem; */
}
.div-img {
  margin-top: 20%;
}
.card1 {
 width: 34rem;
  height: 18rem;
  margin-left: 35rem;
  elevation: 20px;
  margin-top: -18rem;

}
.div-img1 {
  margin-top: 4rem;
  margin-left: 13.5rem;
}
.div-img11 {
  margin-top: 2rem;
  margin-left: 17rem;
  /* margin-left: -30rem; */
  
}
.black {
  color: #000000;
  font-family: Nunito, sans-serif;
  font-weight: 400;
}
.black1 {
  color: #000000;
  font-family: Nunito, sans-serif;
  font-weight: 400;
  font-size: 18px;
  margin-top: 1rem;
  /* background-color: darkblue; */
  width: 800px;
  margin-left: -4.5%;
}
.black2 {
  
  font-size: 18px;
  font-family: sans-serif;
  font-weight: 400;
}
.move{
  margin-left: 14rem;
  margin-top: -11rem;
  
  
}
.slid {
  margin-top: -10%;
  margin-left: 0.1rem;
}
.text_last {
  font-size: 16px;
  width: 25%;
  margin-top: 1rem;
  margin-left: 0.1rem;
  font-family: Nunito, sans-serif;
  
}
.text_last1 {
  font-size: 16px;
  width: 25%;
  margin-top: 1%;
  margin-left: 0.1rem;
  font-family: Nunito, sans-serif;
}
.qq {
  width: 65rem;
  /* background-color: hotpink; */
  margin-left: 20.5rem;
  margin-top: 10rem;
}
.bx {
  margin-left: -10rem;
  margin-top: -22.7rem;
  width: 100%;
}
.boxx {
  margin-left: 9rem;
  margin-top: -32.35rem;
  width: 100%;
}
.boxx1 {
  margin-left: 28rem;
  width: 100%;
  margin-top: -32.35rem;
}
.boxx2 {
  margin-left: 47rem;
  width: 100%;
  margin-top: -32.35rem;
}
.mainbon {
  background-color: blueviolet;
}
.black2 {
  color: #000000;
  font-size: 11px;
  margin-bottom: -4rem;
  width: 600px;
  margin-left: -7.5%;
}
.black00 {
  color: #000000;
  font-size: 18px;
  width: 600px;
  margin-left: 36%;
  margin-top: 1rem;
}
.black3 {
  color: #000000;
  font-size: 18px;
  margin-top: 0.5rem;
  margin-left: 25rem;
  width: 20rem;
}
.black4 {
  color: #000000;
  font-size: 18px;
  margin-top: 4.5rem;
  margin-left: 15%;
  width: 50rem;
}
.text31 {
  /* background-color: brown; */
  width: 55rem;
  font-family: Nunito, sans-serif;
  font-size:26px;
  font-weight: bold;
  height: 160px;
  margin-top: -1rem;
  margin-left: 29rem;
}
.text310 {
  /* background-color: brown; */
  width: 55rem;
  font-family: Nunito, sans-serif;
  font-size: 26px;
  font-weight: bold;
  height: 160px;
  margin-top: 3.5rem;
  margin-left: 25.5rem;
}
.black001 {
  color: #000000;
  font-size: 16px;
  margin-top: 1rem;
  
  margin-left: -3.5%;
  width: 90%;
}
.logo {
  margin-left: 15rem;
  margin-top: 5rem;
}
.img000 {
  margin-left: -6rem;
  margin-top: 29px;
}

.img00 {
  margin-left: 8rem;
  margin-top: -50px;
}
.img10 {
  margin-left: 21rem;

  width: 100%;
  margin-top: -34px;
}
.img11 {
  margin-left: 34rem;

  width: 200%;
  margin-top: -25px;
}
.img12 {
  margin-left: 47rem;

  width: 200%;
  margin-top: -30px;
}
.img13 {
  margin-left: 60rem;

  width: 200%;
  margin-top: -45px;
}
.img14 {
  margin-left: 60rem;
  width: 200%;
  margin-top: 46px;
}
.img15 {
  margin-left: 40rem;
  width: 200%;
  margin-top: -45px;
}
.img16 {
  margin-left: 2rem;
  width: 200%;
  margin-top: -40px;
}
.img17 {
  margin-left: 20rem;
  width: 200%;
  margin-top: -30px;
}
/* * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
} */
</style>