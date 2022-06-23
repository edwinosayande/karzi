<template>
<div id="NinthRoll">
    <div class="contain">
        <div class="container">
            <div class="insidecontainer">
                <div class="tallman">
                    <div class="tallman_img">
                        <img src="../image/tallman.png">
                    </div>
                </div>
                <div class="boxes">
                    <div class="grids">
                        <div class="grid">
                            <div class="subgrid">
                                <h2><span>94</span>%</h2>
                            </div>
                            <p>Cases Won</p>
                        </div>
                         <div class="grid">
                            <div class="subgrid">
                                 <h2><span>863</span></h2>
                            </div>
                            <p>Trusted Client</p>
                         </div>
                          <div class="grid">
                            <div class="subgrid">
                                 <h2><span>126</span>+</h2>
                            </div>
                            <p>Dedicated Lawyer</p>
                          </div>
                           <div class="grid">
                            <div class="subgrid">
                                 <h2><span>25</span>%</h2>
                            </div>
                            <p>Case Dismissed</p>
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
    name: "NinthRoll",
};
</script>
<style scoped>
.contain {
    background: url(../image/stamp.jpg) 50%/cover no-repeat local;
    position: relative;
    background-attachment: fixed;
}
.contain:before {
    content: "";
    background-color: rgba(0,0,0,.7);
    width: 100%;
    height: 100%;
    position: absolute;
    left: 0;
    top: 0;
}
.container {
    max-width: 960px;
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}
.insidecontainer {
    display: flex;
    /* flex-wrap: wrap; */
    margin-right: -15px;
    margin-left: -15px;
}
.tallman {
    flex: 0 0 50%;
    max-width: 50%;
    position: relative;
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
}
.tallman_img {
    position: relative;
    bottom: -55px;
}
img {
    max-width: 100%;
     border-style: none;
}

img, svg {
    vertical-align: middle;
}
.boxes{
    flex: 0 0 50%;
    max-width: 50%;
    position: relative;
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
}
.contain .grids {
    overflow: hidden;
    padding: 125px 0 95px;
    position: relative;
}
.contain .grids .grid{
    width: 48%;
    float: left;
    padding: 50px 0 40px;
    margin-right: 5px;
    background: hsla(0,0%,100%,.2);
    margin-bottom: 5px;
    text-align: center;
}
.contain .grids .grid h2 {
    font-size: 50px;
    font-weight: 700;
    color: #fff;
    margin: 0;
    line-height: 10px;
    font-family: Josefin Sans,sans-serif;
        text-align: center;
}
.contain .grids .grid p {
    font-size: 18px;
    font-weight: 400;
    color: #ddd;
    padding-top: 15px;
    margin-bottom: 0;
}
p{
    line-height: 30px;
    margin-top: 10px;
    
}

</style>