<template>
<div id="ThirdRoll">
  <div class="wrap">
    <div class="ladyimg">
      <img src="../image/lady.png" />
    </div>
     <div class="play_btn">
      <span class="span_img"><img style="width:50px" src="../image/btn.png"></span>
      </div>
    <div class="wrap2">
    <div class="head_text">
      <h2>About Us</h2>
    </div>
    <div class="p_text">
      <p>Contrary to popular belief, Lorem Ipsum is not simply random text. It <br>has roots in a piece of classNameical Latin literature from 45 BC,
         making <br>it over 2000 years old. Richard McClintock, a Latin professor at ,</p>
         <p>and going through the cites of the word in classNameical literature, <br>discovered the undoubtable source. Lorem Ipsum 
           comes from sections<br> 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum</p>
    </div>
    <div class="btn">
      <button>More About Us</button>
    </div>
    <div class="signature">
    <img src="../image/signature.png" />
    </div>
  </div>
  </div>
  </div>

</template>
<script>
export default {
    name: "ThirdRoll",
};
</script>
<style scoped>
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
#ThirdRoll {
   border-top: 1px solid #ddd
}
.wrap {
    width: 100%;
    display: flex;
    margin-top: 100px;
    
   
}
.wrap2 {
    padding-left: 0;
    justify-content: center;
    width: 100%;
    height: 100%;
    flex: 0 0 50%;
    max-width: 50%;
    margin-left: 115px;
}
.ladyimg img {
    padding: 13px;
    border: 1px solid #ffc7b1;
    width: 100%;
    margin-left: 70px;
    height: 95%;
      background: rgba(0,0,0,.4);
    content: "";
}

.p_text {
     margin-bottom: 20px;
    color: #333;
    line-height: 30px;
    font-size: 16px;
    text-align: left;
}
.head_text {
  font-size: 20px;
    font-weight: 700;
    color: #444;
    padding-bottom: 20px;
    margin-bottom: 35px;
    position: relative;
    margin-top: 55px;
    font-family: Josefin Sans,sans-serif;
     
}
.signature {
      max-width: 100%;
      margin-top: 20px;
}
.span_img img {
  position: relative;
  right: 200px;
  top: 50%;
  width: 50px;
  background: -webkit-linear-gradient(left,#9e7044,#d0a15e);
  border-radius: 100%;
  border: 1px solid #d0a15e;
  animation: rotate360 1.2s linear infinite;  /* animation set */
  animation-play-state: paused;               /* put paused */
}
.span_img img:hover {
  animation-play-state: running; 
}
@keyframes rotate360 {                        /* keyframes of animation */
  to { transform: rotate(360deg); }           
}
</style>