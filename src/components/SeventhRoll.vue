<template>
<div id="SeventhRoll">
<div class="contact-area section-padding">
    <div class="container">
        <div class="row">
            <div class="col-lg-5">
                <div class="contact-text">
                    <h2>Are You Interest To Contact With Us?</h2>
                    <p>Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classNameical Latin literature from 45 BC.</p>
                    <div class="contact-sub">
                        <div class="contact-icon">
                            <i class="fa fa-map-marker" aria-hidden="true">
                                <img class="img_location" src="../image/locationimg.png">
                            </i>
                            </div>
                            <div class="contact-c">
                                <h4>Our Location</h4>
                                <span>245 King Street, Touterie Victoria 8520 Australia</span>
                                </div>
                                </div>
                                <div class="contact-sub">
                                    <div class="contact-icon">
                                        <i class="fa fa-phone" aria-hidden="true">
                                            <img class="img_phone" src="../image/phoneimg.png">
                                        </i>
                                        </div>
                                        <div class="contact-c">
                                            <h4>Phone</h4>
                                            <span>0-123-456-7890</span>
                                            </div>
                                            </div>
                                            <div class="contact-sub">
                                                <div class="contact-icon">
                                                    <i class="fa fa-envelope-o" aria-hidden="true"><img class="img_mail" src="../image/mail.png"></i>
                                                    </div>
                                                    <div class="contact-c">
                                                        <h4>Email</h4>
                                                        <span>sample@gmail.com</span>
                                                        </div>
                                                        </div>
                                                        </div>
                                                        </div>
                                                        <div class="col col-lg-7 col-md-12 col-sm-12">
                                                            <div class="contact-content">
                                                                <div class="contact-form">
                                                                    <form>
                                                                        <div class="contact-form form-style row">
                                                                            <div class="name_phone">
                                                                            <div class="col-12 col-lg-6">
                                                                                <div class="name">
                                                                                <input type="text" placeholder="Your Name*" id="fname" name="name" value="">
                                                                                <p></p>
                                                                                </div>
                                                                                </div>
                                                                                <div class="col-12  col-lg-6">
                                                                                    <div class="ph">
                                                                                    <input type="text" placeholder="Phone" id="number" name="number" value="" class="phone">
                                                                                    <p></p>
                                                                                    </div>
                                                                                    </div>
                                                                                    </div>
                                                                                    <div class="email_family">
                                                                                    <div class="col-12  col-lg-6">
                                                                                    
                                                                                        <input type="email" placeholder="Your Email" id="email" name="email" value="">
                                                                                        <p></p>
                                                                                        
                                                                                        <div class="col-12  col-lg-6">
                                                                                        
                                                                                            <select class="form-control" name="events">
                                                                                                <option disabled="" value="">Family Law</option>
                                                                                                <option value="1">Criminal Law</option>
                                                                                                <option value="2">Business Law</option>
                                                                                                <option value="3">Personal Injury</option>
                                                                                                <option value="4">Education Law</option>
                                                                                                <option value="5">Drugs Crime</option>
                                                                                                </select>
                                                        
                                                                                                <p></p>
                                                                                                </div>            
                                                                                                </div>
                                                                                                </div>
                                                                                                <div class="col-12 col-sm-12">
                                                                                                    <textarea class="contact-textarea" placeholder="Message" name="notes"></textarea>
                                                                                                    <p></p>
                                                                                                    </div>
                                                                                                    <div class="col-12">
                                                                                                        <button type="submit" class="theme-btn">Appointment</button>
                                                                                                        </div>
                                                                                                        </div>
                                                                                                        </form>
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
    name: "SeventhRoll",
};
</script>
<style scoped>
.section-padding {
    padding: 100px;
    margin-top: 300px;
}
.contact-area {
    background: url(../image/seal.jpg) 50%/cover no-repeat local;
    position: relative;
    background-attachment: fixed;
}
.contact-area:before {
    content: "";
    background-color: rgba(0,0,0,.9);
    width: 100%;
    height: 100%;
    position: absolute;
    left: 0;
    top: 0;
}
.container {
    width: 1140px;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}

.col-lg-5 {
    flex: 0 0 41.666667%;
    width: 41.666667%;
    position: relative;
    right: 50px;
    margin-left: 60px;
    padding-right: 15px;
    padding-left: 15px;
}

.contact-text h2 {
    font-size: 32px;
    font-weight: 700;
    color: #fff;
    margin-bottom: 30px;
    line-height: 50px;
    width: 450px;
}
h2{
    font-family: Josefin Sans,sans-serif;
    margin-top: 0;
}
h2 {
    display: block;
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
}
.contact-text p {
    color: #fff;
}
p {
    line-height: 30px;
    font-size: 16px;
    margin-top: 0;
    margin-bottom: 1rem;
}
.contact-sub {
    margin-top: 30px;
    overflow: hidden;
}
.contact-icon i {
    float: left;
    margin-right: 20px;
    background: #fff;
    width: 50px;
    height: 50px;
    line-height: 55px;
    text-align: center;
    box-shadow: 9px 5px 10px rgb(72 73 121 / 15%);
    -webkit-border-radius: 5px;
    font-size: 20px;
    color: #d0a15e;
}
.fa {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
}
.contact-c {
    position: relative;
    bottom: 30px;
    overflow: hidden;
}
.contact-c h4 {
    font-size: 20px;
    font-weight: 700;
    color: #fff;
}
h4{
    font-family: Josefin Sans,sans-serif;
    margin-bottom: 0.5rem;
    line-height: 1.2;
    margin-top: 0;
}
h4 {
    display: block;
    margin-block-start: 1.33em;
    margin-block-end: 1.33em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
}
.contact-c {
    overflow: hidden;
}
.contact-c span {
    font-size: 16px;
    font-weight: 400;
    color: #fff;
}

.col-lg-7 {
    position: relative;
    right: 100px;
    flex: 0 0 50.333333%;
    max-width: 58.333333%;
}
.contact-content {
    margin-top: 5x;
    margin-left:100px;
}
.contact-form {
    width: 50%;
}
.row {
    display: flex;
    flex-wrap:wrap;
    margin-right: -15px;
    margin-left: -15px;
}
.name {
    width: 250px;
    position: relative;
    right: 40px;
}
.ph{
    max-width: 200px;
    position: relative;
    right: 155px;
    bottom: 0px;
    top: 1px;
}
.name_phone {
    position: relative;
    top: 100px;
    left: 5px;
    display: flex;
}

.contact-text {
    width: 400px;
    margin-left: 90px;
}
.contact-area form {
    /* overflow: hidden; */
    margin: 0 -15px;
}
.contact-area form div {
    padding: 0 15px 15px;
}

 .contact-area form div {
    padding: 0 15px 15px;
}
.email_family {
    position:relative;
    top: 80px;
    right: 18px;
}

.col-lg-6 {
    flex: 0 0 50%;
    max-width: 50%;
}
.col-12 .col-lg-6{
    position: relative;
    width: 190px;
    left: 300px;
    bottom: 62px;
}
.contact-area form input {
    background: hsla(0,0%,100%,.2);
    height: 40px;
    padding: 3px 15px;
    color: #fff;
    border-radius: 0;
    box-shadow: none;
    border: none;
    width: 100%;
}
input {
    overflow: visible;
    margin: 0;
    font-family: inherit;
    font-size: inherit;
    line-height: inherit;
}
.contact-form p {
    color: red;
}
.contact-area select.form-control:not([size]):not([multiple]) {
    height: 50px;
    padding: 0px 15px;
    color: #999;
    font-size: 14px;
    border-radius: 0;
    box-shadow: none;
    border: none;
    position: relative;
    appearance: none;
    background: hsla(0,0%,100%,.2) url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAkAAAAGCAYAAAARx7TFAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAyZpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuNi1jMDY3IDc5LjE1Nzc0NywgMjAxNS8wMy8zMC0yMzo0MDo0MiAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RSZWY9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZVJlZiMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIENDIDIwMTUgKFdpbmRvd3MpIiB4bXBNTTpJbnN0YW5jZUlEPSJ4bXAuaWlkOjk1QjUzNDMzOEIwODExRTdBMkIzQTQyMTQzNjA5MEJBIiB4bXBNTTpEb2N1bWVudElEPSJ4bXAuZGlkOjk1QjUzNDM0OEIwODExRTdBMkIzQTQyMTQzNjA5MEJBIj4gPHhtcE1NOkRlcml2ZWRGcm9tIHN0UmVmOmluc3RhbmNlSUQ9InhtcC5paWQ6OTVCNTM0MzE4QjA4MTFFN0EyQjNBNDIxNDM2MDkwQkEiIHN0UmVmOmRvY3VtZW50SUQ9InhtcC5kaWQ6OTVCNTM0MzI4QjA4MTFFN0EyQjNBNDIxNDM2MDkwQkEiLz4gPC9yZGY6RGVzY3JpcHRpb24+IDwvcmRmOlJERj4gPC94OnhtcG1ldGE+IDw/eHBhY2tldCBlbmQ9InIiPz7Dl6ZeAAAAY0lEQVR42mKcN3/+GQYGhorEhIQ9DGhg/oIF5UDKmAlI3APiVUABFywKOoD4LBPQhDAgYw+yQiQFIBs6Gf///w/TuQpIgRStBuI0mAKQHFwRksJQZAVgAFKEjIEeCUUXAwgwAC30Q/f8tXHIAAAAAElFTkSuQmCC) no-repeat calc(100% - 15px) 50%;
}
.form-control {
    display: block;
    width: 120%;
    font-weight: 400;
    line-height: 1;
    transition: border-color .15s ease-in-out,box-shadow .15s ease-in-out;
}
select {
    word-wrap: normal;
    text-transform: none;
    margin: 0;
    font-family: inherit;
}
option {
    font-weight: normal;
    display: block;
    white-space: nowrap;
    min-height: 1.2em;
    padding: 0px 2px 1px;
}
.contact-area select.form-control:not([size]):not([multiple]) {
        font-size: 14px;
}

p {
    color: #666;
    line-height: 30px;
    font-size: 16px;
    margin-top: 0;
    margin-bottom: 1rem;
}
.contact-area form textarea {
    height: 150px;
    padding: 15px 200px;
}
.contact-area form textarea {
    background: hsla(0,0%,100%,.2);
    color: #fff;
    border-radius: 0;
    box-shadow: none;
    border: none;
    width: 100%;
}
textarea {
    overflow: auto;
    resize: vertical;
}
button, input, optgroup, select, textarea {
    margin: 0;
    font-family: inherit;
    font-size: inherit;
    line-height: inherit;
}
.col-12 {
    flex: 0 0 100%;
    max-width: 100%;
     position: relative;
    width: 100%;
}
.theme-btn {
    background: #9e7044;
    font-size: 15px;
    font-weight: 700;
    color: #fff;
    padding: 9px 25px;
    border: 1px solid #9e7044;
    text-transform: capitalize;
    display: inline-block;
    transition: all .3s;
}
[type=submit]:not(:disabled), button:not(:disabled) {
    cursor: pointer;
}
[type=submit], button {
    -webkit-appearance: button;
}
button {
    outline: none;
    overflow: visible;
    margin: 0;
    font-family: inherit;
    line-height: inherit;
    border-radius: 0;
}
.img_location{
    width:20px;
}
.img_phone{
    width:20px;
}
.img_mail{
    width:20px;
}
</style>