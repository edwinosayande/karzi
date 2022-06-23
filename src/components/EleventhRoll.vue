<template>
<div id="EleventhRoll">
<div class="footer_container">
    <div class="top">
        <div class="contain">
            <div class="row">
                <div class="content">
                    <div class="footer_logo">
                        <img src="../image/secondlogo.png">
                    </div>
                    <p>Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classNameical Latin literature</p>
                </div>
                 <div class="content">
                    <div class="practice">
                        <h3>Quick Link</h3>
                        <ul>
                            <li><a href="/">Home</a></li>
                            <li><a href="/">Practice Area</a></li>
                            <li><a href="/">Our Team</a></li>
                            <li><a href="/">Recent Case</a></li>
                            <li><a href="/">Our Blog</a></li>
                        </ul>
                    </div>
                 </div>
                  <div class="content">
                     <div class="practice">
                        <h3>Practice Area</h3>
                        <ul type="">
                            <li><a href="/">Family Law</a></li>
                            <li><a href="/">Criminal Law</a></li>
                            <li><a href="/">Parsonal Injury</a></li>
                            <li><a href="/">Real Estate Law</a></li>
                            <li><a href="/">Business Law</a></li>
                        </ul>
                    </div>
                  </div>
                   <div class="content">
                     <div class="practices">
                        <h3>NewsLetter</h3>
                        <p>Samsa was a travelling salesman and above it there hung a picture that he had recently

                        </p>
                        <form>
                            <div class="input">
                                <input type="email" class="form_input" placeholder="Email Address*" required>
                            </div>
                            <div class="submit">
                                <button type="submit">
                                    <i class="fa fa-envelope-o" aria-hidden="true"><img class="img_icon" src="../image/em.png"></i>
                                </button>
                            </div>
                        </form>
                    </div>
                   </div>
            </div>
        </div>
    </div>
    <div class="footer_bottom">
        <div class="bottom_container">
            <div class="bottom_contain">
                <div class="row">
                    <div class="content">
                        <span>Privacy Policy | &copy; 2020 <a href="/"><span class="kazi">Kazi</span></a>. All Right Reserved</span>
                    </div>
                    <div class="content_div">
                        <ul class="list_items">
                            <li><a href="/"><i class="fan fa-facebook" aria-hidden="true"><img class="img_icon" src="../image/fb.png"></i></a></li>
                             <li><a href="/"><i class="fan fa-twitter" aria-hidden="true"><img class="img_icon" src="../image/tw.png"></i></a></li>
                              <li><a href="/"><i class="fan fa-linkedin" aria-hidden="true"><img class="img_icon" src="../image/lk.png"></i></a></li>
                        </ul>
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
    name: "EleventhRoll",
};
</script>
<style scoped>
.footer_container {
    margin-top: 100px;
    background: #231b0e;
}
.top {
    padding: 80px 0 50px;
}
.contain {
    max-width: 960px;
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}
.row {
    display: flex;
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
}
.content{
    flex: 0 0 20%;
    max-width: 25%;

    
    position: relative;
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
}
.footer_logo {
    margin-bottom: 30px;
}
img {
    max-width: 100%;
    border-style: none;
}
img, svg {
    vertical-align: middle;
}
.top p {
    font-size: 14px;
    line-height: 26px;
    color: #ddd;
}
p{
    margin-top: 0;
    margin-bottom: 1rem;
}
.practice{
    margin-bottom: 30px;
}
.practices{
    margin-bottom: 30px;
}
.top h3 {
    font-size: 25px;
     color: #fff;
    margin-bottom: 20px;
    font-family: Josefin Sans,sans-serif;
}
h3{
    font-weight: 500;
    line-height: 1.2;
    margin-top: 0;

}
ul {
    list-style-type: none;
    padding-left: 0;
    margin: 0!important;
    margin-bottom: 0;

}
li {
    display: list-item;
    text-align: -webkit-match-parent;
}
.practice ul li a {
    padding-top: 10px;
    display: block;
    transition: all .3s;
    position: relative;
    padding-left: 30px;
}
.footer-link ul li a {
    padding-top: 10px;
    display: block;
    -webkit-transition: all .3s;
    transition: all .3s;
    position: relative;
    padding-left: 30px;
}
.top a {
    color: #ddd;
    text-decoration: none;
}
.practice ul li a:before {
    font-family: FontAwesome;
    content: "\f101";
    font-size: 15px;
    position: absolute;
    left: 5px;
    top: 12px;
    border-radius: 50%;
}
.top .practices form {
    margin-top: 25px;
    position: relative;
}
.top .practices form input {
    background: rgba(68,68,68,.64);
    height: 50px;
    color: #fff;
    padding: 6px 15px;
    border: none;
    box-shadow: none;
}
.form_input {
    display: block;
    width: 100%;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    border: 1px solid #ced4da;
    border-radius: 0.25rem;
    transition: border-color .15s ease-in-out,box-shadow .15s ease-in-out;
}
input{
     overflow: visible;
    margin: 0;
    font-family: inherit;
}
.top .practices form .submit {
    position: absolute;
    right: 20px;
    top: 50%;
    transform: translateY(-50%);
}
.top .practices form .submit button {
    background: transparent;
    border: 0;
    outline: 0;
    font-size: 20px;
    color: #fff;
}
[type=submit]:not(:disabled), button:not(:disabled) {
    cursor: pointer;
}
button {
    text-transform: none;
    overflow: visible;
    margin: 0;
    font-family: inherit;
    line-height: inherit;
    border-radius: 0;
}
.fa {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
}
.footer_bottom {
    max-width: 960px;
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}
.bottom_contain{
    border-top: 1px solid hsla(0,0%,100%,.08);
    padding: 30px 0;
}
.bottom_contain span {
    font-size: 14px;
        color: #ddd;
}
.bottom-contain span a {
    color: #d0a15e;
}
.bottom-contain ul {
    justify-content: flex-end;
}
.list_items {
    display: flex!important;
}
ul {
    list-style-type: none;
    padding-left: 0;
    margin: 0!important;
    margin-bottom: 0;
}
.bottom_contain ul li {
    padding-right: 15px;
}
.bottom-contain ul li a {
    color: #ddd;
    transition: all .2s;
}
.fan {
    position: relative;
    left: 570px;
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
}
span a .kazi{
    color:#d0a15e;
}
.img_icon{
    width: 30px;
}
</style>