
import NavigationBar from '../components/NavigationBar.vue';

<template>
    <div>
    <div>
    <div>
        <NavigationBar/>
    </div>
    <div class="words">
        <h1>contact me:</h1>
        <br>
    </div>
    <div class="contact">
        <button class="button" v-on:click="onButtonClick"> email me! </button>
        <button class="linkedin" v-on:click="onButtonClick2"> <a href="https://www.linkedin.com/in/melisarz"> <i class="fa fa-linkedin-square"></i></a> </button>
    </div>
    </div>
    <div>
        <Footer/>
    </div>
    </div>
</template>
<style>
 @import url('https://fonts.googleapis.com/css2?family=Sofia+Sans+Semi+Condensed:wght@200;900&display=swap'); 
 .words{
    font-size: 40px;
	color: black;
    font-family: 'Sofia Sans Semi Condensed', sans-serif;
    text-decoration: none;
    display: flex;
    align-items: center;
    justify-content: center; 
 }
 .contact{
    font-size: 40px;
	color: black;
    font-family: 'Sofia Sans Semi Condensed', sans-serif;
    text-decoration: none;
    display: flex;
    align-items: center;
    justify-content: center;
 }
 .button{
    padding: 15px 25px;
    font-size: 20px;
    border-radius: 10px;
    background-color: #D8E2DC;
 }
 .linkedin{
    padding: 15px 25px;
    font-size: 20px;
    border-radius: 10px;
    color: black;
    text-decoration: none;
    background-color: #D8E2DC;
 }
 #email{
    text-decoration: none;
    color: black;
 }
 .fa-linkedin {  
  background: #007bb5;  
  color: white;  
} 
</style>
<script>
export default {
  methods: {
    onButtonClick() {
        location.href = "mailto:example@example.com";
    },
    onButtonClick2() {
        location.href = "https://www.linkedin.com/in/melisarz"
    }
  }
}
</script>