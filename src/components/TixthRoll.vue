<template>
<div id="SixthRoll">
<div class="testimonial-area section-padding">
<div class="container">
<div class="testimonial-active">
<div class="slick-slider slick-initialized" dir="ltr">
<div class="slick-list">
<div data-index="-2" tabindex="-1" class="slick-slide slick-cloned" aria-hidden="true" style="width: 555px;">
<div>
    <div class="align_all">
<div class="my-testimonial" tabindex="-1" style="width: 100%; display: inline-block;">
<div class="inner-content">
<div class="content">
<div class="image-box">
<img src="../image/david.jpg" alt="" />
</div>
<div class="quote-icon">
    <i class="fi flaticon-right-quote"><img class="quotation" src="../image/quotation.png"></i>
    </div>
    <div class="wrap_text">
    <h4>David Millar</h4>
    <div class="designation">CEO of America BDS</div>
    <div class="text">The greatest discovery of all time is that a person can changes his futures by some merely changing his attitude &amp; some life style.</div>
    </div>
    </div>
    </div>
    </div>

    <div class="my-testimonial" tabindex="-1" style="width: 100%; display: inline-block;">
<div class="inner-content">
<div class="content">
<div class="image-box">
<img src="../image/david.jpg" alt="" />
</div>
<div class="quote-icon">
    <i class="fi flaticon-right-quote"><img class="quotation" src="../image/quotation.png"></i>
    </div>
    <div class="wrap_text">
    <h4>Ketly Williams</h4>
    <div class="designation">CEO of Details</div>
    <div class="text">The greatest discovery of all time is that a person can changes his futures by some merely changing his attitude &amp; some life style.</div>
    </div>
    </div>
    </div>
    </div>

    </div>
    </div>
    </div>
    </div>
        </div>
        </div>
        </div>
        </div>
    </div>

</template>
<script>
export default {
    name: "TixthRoll",
};
</script>
<style scoped>
.section-padding {
    padding: 100px;
}
.container {
    max-width: 1140px;
}
.slick-slider {
    position: relative;
    display: block;
     box-sizing: border-box;
      user-select: none;
     touch-action: pan-y;
    -webkit-tap-highlight-color: transparent;
    color: transparent;
}
.slick-list .slick-slider {
    position: relative;
    display: block;
}

.slick-track{
    position:relative;
    top: 0;
    left: 0;
    display: block;
    margin-left: auto;
    margin-right: auto;
}
.slick-track:before{
    display: table;
    content:"";
}
.slick-initialized .slick-slide{
    display: block;
}
.slick-slide{
    float: left;
    height: 100%;
    min-height: 1px;
}
.my-testimonial .inner-content{
    padding: 30px 25px 0px 20px;
    position: relative;
    background: #f5f5f5;
    margin: 15px;
}
.my-testimonial .inner-content .content{
    padding-left: 0px;
    position: relative;
    top: 20px;
}
.testimonial .inner-content .image-box{
    border-radius: 50%;
    height: 90px;
    left: 0;
    margin-bottom: 20px;
    overflow: hidden;
    top: 0;
    width: 90px;
}
.slick-slide img {
    display: block;
}
img{
    max-width: 100px;
    border-style: none;
    border-radius: 50%;
}
img svg{
    vertical-align: middle;
}
.my-testimonial .inner-content .quote-icon{
    color: #d0a15e;
    font-size: 0px;
    line-height: 1em;
    position: absolute;
    right: 0;
    top: 0;
}
.quotation{
    width: 40px;
}
.my-testimonial .inner-content h4{
    color: #444;
    font-size: 18px;
    font-weight: 700;
    position: relative;
    text-transform: uppercase;
    font-family: sans-serif;
    line-height: 1.2;
    margin-top: 0;
}
.my-testimonial .inner-content .designation {
    color: #666;
    margin-bottom: 12px;
    position: relative;
}
 .text{
    color: #606060;
    font-size: 16px;
    margin-bottom: 5px;
    position: relative;
       margin-right: 40px;
       text-align: justify;
    /* bottom: 50px; */
}
.wrap_text{
    position: relative;
    bottom: 100px;
    margin-left: 120px;
}
.slick-track:after{
    clear:both;
    display: table;
    content: "";
}
.slick-dots{
        position: absolute;
        bottom: 25px;
        width: 100%;
        list-style: none;
        text-align: center;

    }
    .slick-dots{
     
    }
    .align_all{
        display: flex;
        width: 1070px;
        margin-left: 150px;
    }

</style>