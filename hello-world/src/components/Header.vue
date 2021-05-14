<template>
  <!-- <div class="header">
      
     
      
       <hr class="solid">  -->
  <!-- </div> -->
  <v-row class="header">
    <v-col cols="12" xs="12" md="6" lg="6">
      <v-img
        class="img"
        max-width="200px"
        src="https://upkey.com/images/icons/logo.svg"
      />
      
    </v-col>
    <div class="text">
      <p>Tools </p>
     
      <p class="text1">Programs</p>
    </div>
      <v-col cols="12" xs="12" md="6" lg="6">
    <v-btn  color="rgba(2, 174, 255)" class="btn1">
      Get your dashboard
    </v-btn >
    <v-btn
     color="rgba(2, 174, 255)"
    elevation="5"
    outlined
    class="btn2"
>Login</v-btn>
<hr class="solid " />
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: "Header",
  props: {},
  data() {
    return {};
  },
  methods: {},
  computed: {},
  watch: {},
  created() {},
  mounted() {},
  beforeDestroy() {},
};
</script>

<style scoped>
.header {
  /* background-color: rgb(243, 168, 168); */
  width: 150rem;
  height: 100px;
}
.text {
  width: 2%;
  margin-left: -55rem;
  margin-top: 2.9rem;
  font-size: 16px;
  font-family: Nunito, sans-serif;
  font-weight: bold;
  color: rgb(70, 69, 69);
  
}
.text1 {
  margin-left: 5rem;
  margin-top: -1.13rem;
  
}
.btn1{
   margin-left: 55rem;
   margin-top: 1.1rem;
  font-family: Nunito, sans-serif;
  font-weight: bold;
  text-transform: none;
  color: white !important;
  min-height: 3.3rem;
  background-color: blueviolet;  
  
}
.btn2{
   margin-left: 48.5rem;
   margin-top: -4.6rem;
   width: 5rem;
  font-family: Nunito, sans-serif;
  font-weight: bold;
  text-transform: none;
  
  min-height: 3.3rem;
  color: rgb(226, 19, 19);
  
  
}
/* .text2 {
    background-color: rgb(90, 75, 75);
    width: 20%;
    margin-top: -1.2rem;
    margin-left: 4rem;
  } */
hr.solid {
  border-top: 1px solid rgb(211, 206, 206);
  margin-top: 0.2rem;
  margin-left: -25rem;
  width: 300rem;
}
.img {
  margin-left: 9.5rem;

  width: 7rem;
  margin-top: 1.5rem;
}
</style>