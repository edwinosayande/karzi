<template>
<div id="EightRoll">
    <div class="container">
        <div class="container1">
        <span>Meet Our Experts</span>
        <h2>Qualified Attorneys</h2>
    </div>
    <div class="all_img">
       
    <div class="first_img">
        <div class="social_1st">
<ul>
    <li><a class="hi" href="/"><i class="fa fa-facebook" aria-hidden="true"></i></a><img class="fb" src="../image/facebook.png"></li>
    <li><a class="hi" href="/"><i class="fa fa-twitter" aria-hidden="true"></i></a><img class="fb" src="../image/twitter.png"></li>
    <li><a class="hi" href="/"><i class="fa fa-linkedin" aria-hidden="true"></i></a><img class="fb" src="../image/linkedin.png"></li>
    </ul>
    </div>
    <img src="../image/firstman.jpg">
    <div class="span_tag">
    <h4>Daniel Danbeldor</h4>
    <span>Family Lawyer</span>
    </div>
    </div>
   
    <div class="second_img">
        <div class="social_1st">
<ul>
    <li><a class="hi" href="/"><i class="fa fa-facebook" aria-hidden="true"></i></a><img class="fb" src="../image/facebook.png"></li>
    <li><a class="hi" href="/"><i class="fa fa-twitter" aria-hidden="true"></i></a><img class="fb" src="../image/twitter.png"></li>
    <li><a class="hi" href="/"><i class="fa fa-linkedin" aria-hidden="true"></i></a><img class="fb" src="../image/linkedin.png"></li>
    </ul>
    </div>
    <img src="../image/secondwoman.jpg">
    <div class="span_tag">
    <h4>Darcy Alec</h4>
    <span>Criminal Lawyer</span>
    </div>
    </div>
 
    <div class="third_img">
        <div class="social_1st">
<ul>
    <li><a class="hi" href="/"><i class="fa fa-facebook" aria-hidden="true"></i></a><img class="fb" src="../image/facebook.png"></li>
    <li><a class="hi" href="/"><i class="fa fa-twitter" aria-hidden="true"></i></a><img class="fb" src="../image/twitter.png"></li>
    <li><a class="hi" href="/"><i class="fa fa-linkedin" aria-hidden="true"></i></a><img class="fb" src="../image/linkedin.png"></li>
    </ul>
    </div>
    <img src="../image/thirdman.jpg">
    
    <div class="span_tag">
    <h4>Akecgander Harry</h4>
    <span>Business Lawyer</span>
    </div>
    </div>
</div>

    </div>
    </div>
</template>
<script>
export default {
    name: "EightRoll",
};
</script>
<style scoped>
#EightRoll{
    padding: 100px 0 70px;
}
.container1{
    text-align: center;
    margin-top: 0px;
}
.container h2:before {
    content: "";
    position: absolute;
    left: 0;
    bottom: 0;
    width: 80px;
    height: 4px;
    background: #d0a15e;
    border-radius: 20px;
    left: 47%;
}
span{
    font-size: 16px;
    color: #d0a15e;
    font-weight: 600;
    text-transform: capitalize;
    margin-bottom: 10px;
}
h2{
    font-size: 36px;
    font-weight: 700;
    color: #444;
    padding-bottom: 20px;
    margin-bottom: 60px;
    position: relative;
    margin-top: 15px;
}
img{
    width: 300px;
}
.first_img:hover{
    opacity: 1;
}
.all_img{
    display: flex;
    justify-content: center;
}
.span_tag{
    text-align: center;
    padding: 15px 0px;
    background: #f5f5f5;
    max-width: 310px;
    margin: -60px 20px auto;
    position:relative;
    z-index: 102;
    border-radius: 10px;
    box-shadow: 1px 1px 5px rgba(0 0 15 /4%);
}
.first_img{
    /* background: rgba(158,112,68,.95); */
    margin-right: 30px;
    
    /* z-index: 2; */
}
.third_img{
    margin-left: 30px;
}
.fa{
    color: #d0a15e; 
}
li{
     background: #fff;
     margin-top: 0;
    width: 50px;
    height: 50px;
    line-height: 55x;
    text-align: center;
    box-shadow: 9px 5px 10px rgb(72 73 121 / 15%);
    font-size: 20px;
    color: #d0a15e;
    font: normal normal normal 14px/1 FontAwesome;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
}
.social_1st{
position: absolute;
top: 0;
left:0;
display: flex;
z-index: 2;
justify-content: center;
flex-direction: column;
opacity: 0;
}
 .social_1st:hover{
    opacity: 1;
}
ul{
    display: flex;
    list-style-type: none;
    padding-left: 0;
    margin: 0! important;
    margin-bottom: 0;

    margin-block-start: 1em;
     margin-block-end: 1em;
      margin-inline-start: 0px;
       margin-inline-end: 0px;
       padding-inline-start: 40px;
}
.fb{
    width: 20px;
     margin-top: 15px;
}
.social_1st{
    position: relative;
    top: 200px;
    left: 50px;
}

.list1 {
  transform: rotateY(180deg);
} 

.list2 {
  transform: rotateX(180deg);
}

.list3 {
  transform: rotateX(180deg) rotateY(180deg);
}
</style>