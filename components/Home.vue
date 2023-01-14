<template>
    <div>
    <div class="picture">
        <img src="/professional photo.JPG" alt =" a picture of Melisa" width="300px"/>
        <p id="text">
            <h1 class="name"> hello, i'm melisa zhang.&nbsp;&nbsp;</h1>
            <h1 class="hand"> <span class="hand"> 👋</span> </h1>
        </p>
    </div>
<div class ="info">
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <p>
        <h2 id="aboutme">about me:</h2>
        <p>
        i'm a current freshman studying computer science at columbia university. welcome to my website! 
        i'm interested in <strong> swe </strong> and look forward to learning more about it!
        i have experience working in three different college labs: the <strong>
            <a id ="link1" href="https://intelligentpower.engr.uga.edu">intelligent power electronics 
        and electric machine laboratory</a>
            </strong> at the <strong>university of georgia</strong>, the 
            <strong>
                <a id ="link2" href="http://xie.uga.edu">xie bio-imaging research lab</a>
            </strong> 
        at the <strong>university of georgia</strong>, and the 
        <strong>
            <a id ="link3" href="http://caid.cs.uga.edu">cortical architecture imaging discovery laboratory</a>
        </strong> at the <strong>university of georgia</strong>. through these interships i've gained important soft 
        skills like communication, leadership, organization while simultaneously learning new technical knowledge.
        </p>

    </p>
    <br>
    <br>
    <br>
</div>
</div>
</template>
<style>
 @import url('https://fonts.googleapis.com/css2?family=Sofia+Sans+Semi+Condensed:wght@200;900&display=swap'); 
#aboutme{
    text-align: center;
}
.info{
    font-size: 25px;
    text-align: center;
}
.picture{  
    padding: 20px;
    float: left;
    padding: 5px;
    font-size: 25px;
	color: black;
    font-family: 'Sofia Sans Semi Condensed', sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    
}
img{
    border: 5px solid #FEC5BB;
    border-radius: 50%;
}
body {
    background-color: #ffffff;
}
#text{
    margin-right: 80px;
    font-size: 25px;
}
#link1{
    color: black;
}
#link2{
    color: black;
}
#link3{
    color: black;
}
.hand {
    animation: wave 2s infinite;
  }
  @keyframes wave {
    0% {
      transform: rotate(0deg);
    }
    10% {
      transform: rotate(-15deg);
    }
    20% {
      transform: rotate(12deg);
    }
    30% {
      transform: rotate(-10deg);
    }
    40% {
      transform: rotate(8deg);
    }
    50% {
      transform: rotate(0deg);
    }
    100% {
      transform: rotate(0deg);
    }
  }
 </style>
