<template>
<div class="layer">

     <!--Navbar -->
     <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">
               <img className="d-block w-80" style="height:80px;" src="../assets/logo/logo2.png"/>
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse text-right offset-5" id="navbarNav">
            <ul class="navbar-nav text-uppercase mx-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#" style="font-family: 'Montserrat';font-weight:bold;">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#" style="font-family: 'Montserrat';font-weight:bold;">Introduction</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#" style="font-family: 'Montserrat';font-weight:bold;">Expertise</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#" style="font-family: 'Montserrat';font-weight:bold;">Teams</a>
                </li>
            </ul>
            
            </div>
        </div>
     </nav>
    <!--Akhir Navbar -->
  <div className="card-body">
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active" style="position: relative;top:50px;z-index:3;"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1" style="position: relative;top:50px;z-index:3;"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2" style="position: relative;top:50px;z-index:3;"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="3" style="position: relative;top:50px;z-index:3;"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img class="d-block w-100" style=" height: 500px;" src="../assets/background/create.png" alt="First slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" style=" height: 500px;" src="../assets/background/entrepreneur.jpg" alt="Second slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" style=" height: 500px;" src="../assets/background/computer.jpg" alt="Third slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" style=" height: 500px;" src="../assets/background/code.jpg" alt="Third slide">
          </div>
      
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
    </div>
  </div>
     <!--Akhir Layer-->
</template>

<script setup>
import bootstrap from '../assets/css/bootstrap.css'
import all from '../assets/css/all.css'
import style from '../assets/css/style.css'
</script>

<style>
@import url('https://fonts.gstatic.com');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap');
</style>