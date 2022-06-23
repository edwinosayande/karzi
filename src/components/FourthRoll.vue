<template>
<div id="FourthRoll">
  <div class="header_text">
<span class="area">Area Of Practice</span>
<h3>How Can We Help You</h3>
  </div>
  <div class="border_line"></div>
  <div class="row">
   <div class="col-lg-4 col-md-6 col-12">
  <div class="practice-section">
    <div class="practices-wrapper">
        <div class="practices-icon-wrapper">
            <div class="practice-dot">
                <div class="dots">

                </div>
                </div>
                <i class="fi">
                    <img src="../image/family.png" alt="">
                    </i>
                    </div>
                    <div class="practice-content">
                        <h2>Family Law</h2>
                        <p>It is a long established fact that a reader will be distracted by the readable content of </p>
                        </div>
                        </div>
                        </div>
                        </div>

                         <div class="col-lg-4 col-md-6 col-12">
  <div class="practice-section">
    <div class="practices-wrapper">
        <div class="practices-icon-wrapper">
            <div class="practice-dot">
                <div class="dots">

                </div>
                </div>
                <i class="fi">
                    <img src="../image/personal.png" alt="">
                    </i>
                    </div>
                    <div class="practice-content">
                        <h2>Personal Injury</h2>
                        <p>It is a long established fact that a reader will be distracted by the readable content of </p>
                        </div>
                        </div>
                        </div>
                        </div>

                         <div class="col-lg-4 col-md-6 col-12">
  <div class="practice-section">
    <div class="practices-wrapper">
        <div class="practices-icon-wrapper">
            <div class="practice-dot">
                <div class="dots">

                </div>
                </div>
                <i class="fi">
                    <img src="../image/business.png" alt="">
                    </i>
                    </div>
                    <div class="practice-content">
                        <h2>Business Law</h2>
                        <p>It is a long established fact that a reader will be distracted by the readable content of</p>
                        </div>
                        </div>
                        </div>
                        </div>

                         <div class="col-lg-4 col-md-6 col-12">
  <div class="practice-section">
    <div class="practices-wrapper">
        <div class="practices-icon-wrapper">
            <div class="practice-dot">
                <div class="dots">

                </div>
                </div>
                <i class="fi">
                    <img src="../image/criminal.png" alt="">
                    </i>
                    </div>
                    <div class="practice-content">
                        <h2>Criminal Law</h2>
                        <p>It is a long established fact that a reader will be distracted by the readable content of </p>
                        </div>
                        </div>
                        </div>
                        </div>

                         <div class="col-lg-4 col-md-6 col-12">
  <div class="practice-section">
    <div class="practices-wrapper">
        <div class="practices-icon-wrapper">
            <div class="practice-dot">
                <div class="dots">

                </div>
                </div>
                <i class="fi">
                    <img src="../image/education.png" alt="">
                    </i>
                    </div>
                    <div class="practice-content">
                        <h2>Education Law</h2>
                        <p>It is a long established fact that a reader will be distracted by the readable content of </p>
                        </div>
                        </div>
                        </div>
                        </div>

                         <div class="col-lg-4 col-md-6 col-12">
  <div class="practice-section">
    <div class="practices-wrapper">
        <div class="practices-icon-wrapper">
            <div class="practice-dot">
                <div class="dots">

                </div>
                </div>
                <i class="fi">
                    <img src="../image/realestate.png" alt="">
                    </i>
                    </div>
                    <div class="practice-content">
                        <h2>Real Estate Law</h2>
                        <p>It is a long established fact that a reader will be distracted by the readable content of </p>
                        </div>
                        </div>
                        </div>
                        </div>
                        </div>
  </div>
</template>
<script>
export default {
    name: "FourthRoll",
};
</script>
<style scoped>
.header_text {
    margin-top: 80px;
    text-align: center;
}
#FourthRoll {
    border-top: 1px solid #ddd;
    margin-top: 80px;
    margin-right: 50px;
    margin-left: 50px;
}
.area {
    font-size: 16px;
    color: #d0a15e;
    font-weight: 600;
    text-transform: capitalize;
    margin-bottom: 10px
}
h3 {
    margin-bottom: 60px;
    font-size: 36px;
    font-weight: 700;
    color: #444;
    padding-bottom: 20px;
    /* margin-bottom: 50px; */
    position: relative;
    margin-top: 15px;
}
.practice-section {
        box-sizing: border-box;
        display: block;
}
.practice-section .practices-wrapper {
    text-align: center;
    margin-bottom: 30px;
    background: #fff;
    padding: 85px;
    box-shadow: 0 10px 40px 0 rgb(50 50 50 / 10%);
}
.practices-icon-wrapper {
    position: relative;
    z-index: 1;
    width: 100px;
    height: 100px;
    line-height: 100px;
    border: 1px solid rgba(158,112,68,.25);
    font-size: 50px;
    background: #fff;
    box-sizing: content-box;
    border-radius: 50%;
    color: #d0a15e;
    margin: auto;
}
.practice-section .practices-icon-wrapper .practice-dot:first-child {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
    -webkit-animation: practice-dot_1 2s linear infinite;
    animation: practice-dot_1 2s linear infinite;
    -webkit-animation-play-state: paused;
    animation-play-state: paused;
}
.practice-section .practices-icon-wrapper .practice-dot {
    width: 100%;
    height: 100%;
    left: 56%;
    top: 8%;
}
.practices-icon-wrapper i.fi {
    position: absolute;
    left: 20px;
    top: -11px;
    width: 55px;
}
.row {
    display: flex;
    flex-wrap: wrap;
    margin-right: 55px;
    margin-left: 55px;
}
img {
    max-width: 100%;
}
img, svg {
    vertical-align: middle;
}
img {
    border-style: none;
}
.practice-section .practices-wrapper:hover .practice-dot:first-child {
    -webkit-animation-play-state: running;
    animation-play-state: running;
}
.practice-section .practices-icon-wrapper .practice-dot:first-child {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
    -webkit-animation: practice-dot_1 2s linear infinite;
    animation: practice-dot_1 2s linear infinite;
    -webkit-animation-play-state: paused;
    animation-play-state: paused;
}

.dots {
    width: 15px;
    height: 15px;
    background: #d0a15e;
    border-radius: 50%;
    left: 14px;
    top: 0;
    position: relative;
}
.col-lg-4 {
    flex: 0 0 33.333333%;
    max-width: 33.333333%;
}
h2 {
    font-size: 17px;
    font-weight: 700;
    margin-bottom: 15px;
    margin-top: 10px;
}
p {
    color: #666;
    line-height: 30px;
    font-size: 15px;
}

.header_text h3:before  {
    content: "";
    position: absolute;
    left: 0;
    bottom: 0;
    width: 80px;
    height: 3px;
    background: #d0a15e;
    border-radius: 20px;
    left: 47%;
}
</style>