
import NavigationBar from '../components/NavigationBar.vue';

<template>
    <div>
    <div>
    <div>
        <NavigationBar/>
    </div>
    <div class="words">
        <h1>Contact Me:</h1>
        <br>
    </div>
    <div class="contact">
        <button class="button" v-on:click="onButtonClick"> email me! </button>
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
 #email{
    text-decoration: none;
    color: black;
 }
</style>
<script>
export default {
  methods: {
    onButtonClick() {
        location.href = "mailto:example@example.com";
    }
  }
}
</script>