<template>
<div id="SecondRoll">
<div  class="background"><br><br><br><br><br>
    <div class="writeup">
   <h2>We Fight For Your Justice<br> As Like A Friend</h2>
   <p>There are many variation of passages of Lorem Ipsum available, but the majority have suffered</p>
   <p>alteration in some form, by injected humour, or randomised words.</p>
   <div class="button_div">
   <button>Contact Us Now</button>
   </div>
   </div>
  </div>

  <div class="all">
  <div class="container">
  <div class="img">
    <i class="hi">
    <img src="../image/downloaded.png" />
    </i>
    </div>
    <div class="sptag">
    <span class="ptag"><p class="ppp">Book Your</p></span>
    <span class="ptag2"><h3>Appointment</h3></span> 
    </div>
    </div>

    <div class="container">
  <div class="img">
    <i class="hi">
    <img src="../image/downloadee.png" />
    </i>
    </div>
    <div class="sptag">
    <span class="ptag"><p class="ppp">Get Free</p></span>
    <span class="ptag2"><h3>Expert Advice</h3></span> 
    </div>
    </div>

    <div class="container">
  <div class="img">
    <i class="hi">
    <img src="../image/downloader.png" />
    </i>
    </div>
    <div class="sptag">
    <span class="ptag"><p class="ppp">You Can Easily</p></span>
    <span class="ptag2"><h3>Join Our Team</h3></span> 
    </div>
    </div>
    </div>
    </div>

</template>
<script>
export default {
    name: "SecondRoll",
};
</script>
<style scoped>
.background{
    margin-top: 100px;
    position: relative;
    background-image: url("../4.3e2245bb.jpg");
    width: 100%;
    background-repeat: no-repeat;
    background-size: 100% auto;
    height: 620px;
    
}
.writeup{
    color: #fff;
    z-index: 19;
    padding-bottom: 20px;
    margin-left: 50px;
}
button {
        color: #fff;
        background: -webkit-linear-gradient(left,#9e7044,#d0a15e);
        font-size: 15px;
        font-weight: 600;
        padding: 10px 28px;
        text-transform: capitalize;
        display: inline-block;
        margin-top: 3px;
        border-radius: 5px;
        border: 1px solid #d0a15e;
        position: relative;
        z-index: 11;
        -webkit-transition: all .3s;
        transition: all .3s;
}
h2{
    font-size: 56px;
    font-weight: 600;
    color: #fff;
    line-height: 90px;
    margin: 10px 0 20px;
}
.button_div {
    margin-top: 40px;
}
.container {
  display: block;
  margin-top: 20px;
    margin-bottom: 30px;
    box-shadow: 0 10px 20px 0 rgb(50 50 50 / 10%);
    padding: 5px 10px;
    margin-left: 50px;
    flex-grow: 1;
    column: auto 1;
}
img {
      max-width: 60%;
      vertical-align: middle;
      transition: all .5s;
}
img svg {
  vertical-align: middle;
}
.ppp{
    display: block;
    margin-left: 140px;
}
h3 {
    display: block;
    font-size: 1.17em;
    margin-left: 140px;
    font-weight: bold;
}
.img {
    margin-top: 10px;
    margin-bottom: 10px;
    margin-left: 5px;
    float: left;
    justify-content: center;
    border-style: none;
    box-sizing: border-box;
    border: 1px solid #ddd;
}
 i {
    padding: 0;
    width: 100px;
    height:100px;
    background: #fff;
    line-height: 80px;
    text-align: center;
    margin-right: 10px;
    color: #d0a15e;
    margin-left: 20px;
}
.all {
  display: flex;
flex-direction: row;
margin-right: 50px;

}

</style>