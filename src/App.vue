<template>
<body>
  <div class="container header">
    <img src="./images/logo.png" class="logo">
    <a href="#" class="header-btn">Account</a>
  </div>
  <div class="container movie-deatils">
    <div class="row">
      <div class="col-md-6 left-box">
        <h1>Pluto X Baby Pluto</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium magnam maiores dolores, 
          consequatur inventore cum molestiae porro 
          tempore voluptatem iste ratione quia ipsam ea atque recusandae vitae nesciunt quod quas?</p>
          <p>Artist: </p>
          <div class="artists">
            <img src="http://wethesauce.com/wp-content/uploads/2016/08/future-012.jpg" title="Future">
            <img src="http://wethesauce.com/wp-content/uploads/2016/08/lil_uzi.jpg" title="Lil Uzi Vert">
          </div>
          <a href="#">Stream Now</a>
          <a href="#" class="download-btn"><i class="fa fa-play"></i> Download</a>
      </div>
      <div class="col-md-6 text-center">
        <img src="https://storage.googleapis.com/wethesauce-music/2020/11/11934cd4-01-stripes-like-burberry-m4a-image.jpg" class="movie-ima">
      </div>
    </div>
  </div>
  <div class="container new" id="list">
    <h3>New Albums</h3>
    <div class="row">
      <div class="col-md-4">
        <div class="row">
          <div class="col-6">
            <img src="https://storage.googleapis.com/wethesauce-music/2020/11/944bf441-01-sosamann-mann_family-mp3-image.jpg" alt="">
          </div>
          <div class="col-6">
            <img src="https://storage.googleapis.com/wethesauce-music/2020/10/82e022b7-01-reckless-mp3-image.jpg" alt="">
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="row">
          <div class="col-6">
            <img src="https://storage.googleapis.com/wethesauce-music/2020/10/36c79957-01-let-it-out-feat-myiah-lynnae-mp3-image.jpg" alt="">
          </div>
          <div class="col-6">
            <img src="https://storage.googleapis.com/wethesauce-music/2020/10/f10adb59-01-ty_dolla_ign-intro-mp3-image.jpg" alt="">
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="row">
          <div class="col-6">
            <img src="http://wethesauce.com/wp-content/uploads/2020/03/01-Alone-Again-m4a-image.jpg" alt="">
          </div>
          <div class="col-6">
            <img src="http://wethesauce.com/wp-content/uploads/2020/02/01-lil_baby-get_ugly-m4a-image.jpg" alt="">
          </div>
        </div>
      </div>
    </div>
  </div>
</body>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
body{
  background: linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.8)), url(https://storage.googleapis.com/wethesauce-music/2020/11/11934cd4-01-stripes-like-burberry-m4a-image.jpg) no-repeat center fixed;
  background-position: center;
  background-size: cover;
}
.logo{
  width: 150px;
  margin-top: 18px;
}
.header{
  height: 10%;
}
.header-btn{
  text-decoration: none;
  border-radius: 30px;
  padding: 7px 20px;
  float: right;
  margin-top: 15px;
  color: #fff !important;
  background: #107afd;
  font-weight: 600;
}
.movie-details{
  margin: 3% 0;
}
.left-box{
  color: white;
}
.artists img{
  height: 40px;
  width: 40px;
  margin-right: 10px;
  cursor: pointer;
  border-radius: 50%;
}
.left-box a{
  text-decoration: none;
  border-radius: 30px;
  padding: 7px 10px;
  margin-top: 15px;
  color: #fff !important;
  background: #107afd;
  font-weight: 600;
  display: inline-block;
  margin-right: 10px;
  margin-right: 35px;
}
.download-btn{
  border: 1px solid #fff;
  background: transparent !important;
}
.movie-ima{
  height: 350px;
  box-shadow: -4px 4px 5px 0 #000;
}
.new h3{
  color: #fff;
}
.new img{
  width: 100%;
  margin-top: 15px;
  box-shadow: -4px 4px 5px 0 #000;
  cursor: pointer;
  transition: 1s;
}
.new img:hover{
  transform: translateY(-10px);
}
#list{
  margin-top: 50px;
}
</style>
