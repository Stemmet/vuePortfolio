<template>
  <div class="landing-page">
  <div class="container">
    <div class="info">
      <div id=container>
    Cameron the 
    <div id=flip>
      <div><div>"aspiring web developer"</div></div>
      <div><div>"son"</div></div>
      <div><div>"Friend"</div></div>
    </div>
    Stemmet
  </div>
    </div>
    <div class="image">
      <img src="https://i.postimg.cc/8PZ8vhw5/Cameron-3.jpg">
    </div>
    <div class="clearfix"></div>
  </div>
</div>

</template>

<style scoped>
#container {
  color:#F9AC66;
  text-transform: uppercase;
  font-size:36px;
  font-weight:bold;
  padding-top:250px;  
  width:100%;
  bottom:45%;
  display: block;
  margin: 0px;
  font-family:'League Gothic';
  text-align: center;
  line-height: 1.15;
  z-index: 1;
  height: 100vh;
}

#flip {
  height:45px;
  overflow:hidden;
}

#flip > div > div {
  color:#ED6B5B;
  padding:4px 12px;
  height: 50px;
  margin-bottom:45px;
  display:inline-block;
}

#flip div:first-child {
  animation: show 5s linear infinite;
}

#flip div div {
  background:#F9AC66;
}
#flip div:first-child div {
  background:#F9AC66;
}
#flip div:last-child div {
  background:#F9AC66;
}

@keyframes show {
  0% {margin-top:-270px;}
  5% {margin-top:-180px;}
  33% {margin-top:-180px;}
  38% {margin-top:-90px;}
  66% {margin-top:-90px;}
  71% {margin-top:0px;}
  99.99% {margin-top:0px;}
  100% {margin-top:-270px;}
}

#cameron {
  width: 400px;
  height: 100%; 
  object-fit: cover;
  
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
}

.landing-page .info h1 {
    font-size: 44px;
    margin: 0 0 20px;
    line-height: 1.4;
    color: #5d5d5d;
}

.landing-page .info p {
    margin: 0;
    line-height: 1.6;
    font-size: 15px;
    color: #5d5d5d;
}


.landing-page .image {
    width: 50%;
    float: right;
    margin-top: 35px;
}

.landing-page .image img {
    max-width: 100%;
}


</style>

<script>

</script>
