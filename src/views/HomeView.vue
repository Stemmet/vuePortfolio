<template>
  <div class="landing-page">
  <div class="container">
    <div class="image">
      <img src="https://i.postimg.cc/8PZ8vhw5/Cameron-3.jpg">
    </div>
    <div class="info">
      <div id=container>
    CAMERON THE 
    <div id=flip>
      <div><div>"ASPIRING WEB DEVELOPER"</div></div>
      <div><div>"SON"</div></div>
      <div><div>"FRIEND"</div></div>
    </div>
    STEMMET
    <div id=flip>
      <div><div>EMAIL:</div></div>
      <div><div>INSTAGRAM:</div></div>
      <div><div>CONTACT NO:</div></div>
    </div>
    <div id=flip>
      <div><div>cameronstemmet02@gmail.com</div></div>
      <div><div>@stemmet_</div></div>
      <div><div>+27 62 823 3134</div></div>
    </div>
    </div>
  
    </div>
    <div class="clearfix"></div>
  </div>
</div>

</template>

<style scoped>
#container {
  color:#F9AC66;
  /* text-transform: uppercase; */
  font-size:4rem;
  font-weight:bold;
  padding-top:20px;  
  width:100%;
  bottom:45%;
  display: block;
  margin: 0px;
  font-family:'League Gothic';
  line-height: 1.15;
  z-index: 1;
  height: 100vh;
}

#flip {
  height: 70px;
  overflow:hidden;
  width: 700px;
}

#flip > div > div {
  color:#ED6B5B;
  padding:4px 12px;
  height: 70px;
  margin-bottom:45px;
  display:inline-block;
}

#flip div:first-child {
  animation: show 5s linear infinite;
}



@keyframes show {
  0% {margin-top:-235px;}
  5% {margin-top:0px;}
  33% {margin-top:0px;}
  38% {margin-top:-115px;}
  66% {margin-top:-115px;}
  71% {margin-top:-225px;}
  99.99% {margin-top:-225px;}
  100% {margin-top:-235px;}
}

* {
    box-sizing: border-box;
}

.container {
    width: 1170px;
    padding-right: 15px;
    padding-left: 15px;
    margin: auto;
}


.landing-page .info {
    width: 35%;
    float: left;
    margin-top: 130px;
    z-index: 1;
}

.landing-page .info h1 {
    font-size: 44px;
    margin: 0 0 20px;
    line-height: 1.4;
    color: #5d5d5d;
    z-index: 1;
}

.landing-page .info p {
    margin: 0;
    line-height: 1.6;
    font-size: 15px;
    color: #5d5d5d;
    z-index: 1;
}


.landing-page .image {
    width: 50%;
    float: left;
    margin-top: 35px;
    z-index: -1;
}

.landing-page .image img {
    max-width: 100%;
    height: 90vh;
}


</style>

<script>

</script>
