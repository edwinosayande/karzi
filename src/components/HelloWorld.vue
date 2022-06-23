<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="text_header">
      
    <p style="
          color: #333; margin-left:150px "><img class="clock" src="../image/clock.png">
      Mon - Tues : 6.00 am - 10.00 pm
    </p>
    <p style="margin-left: 105px;  color: #333;"><img class="location" src="../image/blacklocation.png">150 Street, London, USA</p>
    <div class="header_button">
          <button>Free Consultation</button>
        </div>
    </div>
    <div class="combined">
      <div class="second_header">
        <img class="image" src="../download.png" />
        <div class="list">
  <ul>
    <li>
      <a href="https://vuejs.org" target="_blank" rel="noopener">Home</a>
      <ul class="dropdown">
      <li class="sublime"><a href="#SecondRoll">Home One</a></li>
     <li class="sublime"><a href="#ThirdRoll">Home Two</a></li>
       <li class="sublime"><a href="#FourthRoll">Home Three</a></li>
        <li class="sublime"><a href="#FifthRoll">Home Four</a></li>
         <li class="sublime"><a href="#TixthRoll">Home Five</a></li>
          <li class="sublime"><a href="#SeventhRoll">Home six</a></li>
           <li class="sublime"><a href="#EightRoll">Home Seven</a></li>
            <li class="sublime"><a href="#NinthRoll">Home Eight</a></li>
             <li class="sublime"><a href="#TenthRoll">Home Nine</a></li>
              <li class="sublime"><a href="#EleventhRoll">Home Ten</a></li>
    </ul>
    </li>
  </ul>
  <ul>
   <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">About</a></li>
   </ul>
   <ul>
    <li>
      <a href="https://vuejs.org" target="_blank" rel="noopener">Practices</a>
      <ul class="dropdown">
      <li class="sublime">Practice</li>
     <li class="sublime">Practice Details</li>
    </ul>
    </li>
  </ul>
   <ul>
    <li>
      <a href="https://vuejs.org" target="_blank" rel="noopener">Cases</a>
      <ul class="dropdown">
      <li class="sublime">Cases</li>
     <li class="sublime">Cases Single</li>
    </ul>
    </li>
  </ul>
   <ul>
    <li>
      <a href="https://vuejs.org" target="_blank" rel="noopener">Blog</a>
      <ul class="dropdown">
      <li class="sublime"><a></a>Blog Grid</li>
     <li class="sublime">Blog with Sidebar</li>
       <li class="sublime">Blog Full Width</li>
        <li class="sublime">Blog Single Sidebar</li>
       <li class="sublime">Blog Single FullWidth</li>
    </ul>
    </li>
  </ul>
    <ul>
    <li>
      <a href="https://vuejs.org" target="_blank" rel="noopener">Pages</a>
      <ul class="dropdown">
      <li class="sublime">Attorneys</li>
     <li class="sublime">Attorney Single</li>
       <li class="sublime">FAQ</li>
    </ul>
    </li>
  </ul>  
  <ul>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">Contact</a></li>
   </ul>
   </div>
   </div>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
}
</script>

<style scoped>
.clock{
  position: absolute;
  left: 12%;
  width:20px;
}
.location{
  position: absolute;
  left: 31.5%;
  width:20px;
}
.text_header {
    display: flex;
    margin-left: 70px;
    font-size: 15px;
    
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
.header_button{
margin-left: 37%;
}


.second_header{
    display: flex;
    border-top: solid 1px #ddd;;
    margin-left: 50px;
    margin-right: 50px;
    padding: 1px 10px;
   
}
.combined{
    width:100%;
   /* position: -webkit-sticky; */
    position: fixed;
    top: 80px;
    z-index: 999;
    background: #fff;

}

img{
  position: absolute;
  right: 78%;
}
 ul {
            padding: 0;
            list-style: none;
            background: #fff;
            width: 80px;
        }
 
        ul li {
            display: block;
            position: relative;
            line-height: 21px;
            text-align: center;
            
        }
        ul li a {
            display: block;
            color: #333;
            text-decoration: none;
            padding: 10px 15px 10px 0;
            font-size: 15px;
        }
        ul li a:hover {
            color: #333;
            background: #fff;
        }
        ul li ul.dropdown {
            min-width: 220%;
            background: #fff;
            display: none;
            position: absolute;
            z-index: 999;
            left: 0;
        }
        ul li:hover ul.dropdown {
            display: block;
        }
        .sublime{
          padding: 2px 10px;
          border: 1px solid #ddd;;
          height: 50px;
          width: 150px;
        }

        .list {
          display: flex;
          margin-left: 750px;
        }

</style>
