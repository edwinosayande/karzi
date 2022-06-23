<template>
<div id="TenthRoll">
    <div class="container">
        <div class="container1">
        <span>From Our Blog</span>
        <h2>Latest News</h2>
    </div>
    <div class="all_img">
       
    <div class="first_img">
    <img src="../image/handcuff.jpg">
    <div class="span_tag">
    <h3>Justice May For You If <br>You Are Innocent</h3>
    <span class="first_span"><img class="small_img" src="../image/longhair.jpg">By Aliza anne<span class="line">|</span><span>Oct 12,2019</span></span>
    </div>
    </div>
   
    <div class="second_img">
    <img src="../image/redwoman.jpg">
    <div class="span_tag">
    <h3>Justice May For You If<br> You Are Innocent</h3>
    <span class="first_span"><img class="small_img" src="../image/longhair.jpg">By Aliza anne<span class="line">|</span><span>Oct 12,2019</span></span>
    </div>
    </div>
 
    <div class="third_img">
    <img src="../image/lawstamp.jpg">
    
    <div class="span_tag">
    <h3>Justice May For You If <br>You Are Innocent</h3>
    <span class="first_span"><img class="small_img" src="../image/longhair.jpg">By Aliza anne<span class="line">|</span><span>Oct 12,2019</span></span>
    </div>
    </div>
</div>

    </div>
    </div>
</template>
<script>
export default {
    name: "TenthRoll",
};
</script>
<style scoped>
.container{
margin-top: 10%;
 background: #f5f5f5;
}
.container1{
    text-align: center;
    margin-top: 0px;
    line-height: 40px;
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
    font-size: 20px;
    color: #d0a15e;
    font-weight: 600;
    text-transform: capitalize;
    margin-bottom: 10px;
}
.first_span{
    color: #666;
}
.line{
    margin-right: 10px;
    margin-left: 10px;
    color: #666;
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
    width: 400px;
}
.all_img{
    display: flex;
    justify-content: center;
}
h3{
    font-size: 30px;
    text-align: center;
    text-align: justify;
    margin-left: 50px;
    line-height: 50px;
}
.span_tag{
    width: 100%;
    text-align: center;
    padding: 20px 0px;
    background: #fff;
    margin: -4.8px 0px auto;
    position:relative;
    z-index: 102;
}
.first_img{
    margin-right: 30px;
}
.third_img{
    margin-left: 30px;
}
.small_img{
    position: relative;
    top: 20px;
    right: 10px;
    width: 40px;
    border-radius: 100%;
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