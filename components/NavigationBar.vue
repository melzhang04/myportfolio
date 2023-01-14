<template>
        <div class="topnav">
        <nuxt-link id= "home" to="/">MEL.</nuxt-link>
        <nuxt-link id= "resume" to="/resume">resume</nuxt-link>
        <nuxt-link id= "project" to="/projects">projects</nuxt-link>
        <nuxt-link id= "contact" to="/contact">contact</nuxt-link>
    </div>
</template>
<style> 
@import url('https://fonts.googleapis.com/css2?family=Sofia+Sans+Semi+Condensed:wght@200;400;900&display=swap'); 
.topnav{
    font-size: 25px;
    color: black;
    font-family: 'Sofia Sans Semi Condensed', sans-serif;
    width: 100%;
    left: 0;
    text-align: right;
    background-color: #ECE4DB;
    padding: 20px;
}
#home{
    float: left;
    text-decoration: none;
    color: black;
}
#resume{
    text-decoration: none;
    color: black;
}
#project{
    text-decoration: none;
    color: black;
}
#contact{
    text-decoration: none;
    color: black;
}
</style>