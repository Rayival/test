<template>
    <div class="container">
      <h4 class="mt-5 text-center text-md-start">
        Guru & <br> <span class="text-primary">Staf TU</span>
      </h4>
  
      <!-- Statistik Guru dan Staf -->
      <div class="row mt-5 d-flex justify-content-center">
        <div class="col-12 col-sm-6 col-md-3 mb-3">
          <div class="card card-total rounded-4">
            <div class="card-body">
              <h5 class="fw-semibold">80 Orang</h5>
              <p>Total Guru / Pendidik</p>
            </div>
          </div>
        </div>
        <div class="col-12 col-sm-6 col-md-3 mb-3">
          <div class="card card-total rounded-4">
            <div class="card-body">
              <h5 class="fw-semibold">5 Orang</h5>
              <p>Total Guru BP / BK</p>
            </div>
          </div>
        </div>
        <div class="col-12 col-sm-6 col-md-3 mb-3">
          <div class="card card-total rounded-4">
            <div class="card-body">
              <h5 class="fw-semibold">15 Orang</h5>
              <p>Total Staf TU</p>
            </div>
          </div>
        </div>
      </div>
  
      <!-- Daftar Guru -->
      <div class="card card-guru mt-5">
        <h5 class="text-center mt-5">Daftar Guru / Pendidik</h5>
        <div class="row mt-4 justify-content-center mb-5">
          <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card rounded-4 text-center">
              <div class="card-body">
                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="responsive-img">
                <h5 class="fw-semibold mt-4 responsive-text">Nama Guru</h5>
                <p class="responsive-text">Guru Mapel</p>
              </div>
            </div>
          </div>
          <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card rounded-4 text-center">
              <div class="card-body">
                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="responsive-img">
                <h5 class="fw-semibold mt-4 responsive-text">Nama Guru</h5>
                <p class="responsive-text">Guru Mapel</p>
              </div>
            </div>
          </div>
          <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card rounded-4 text-center">
              <div class="card-body">
                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="responsive-img">
                <h5 class="fw-semibold mt-4 responsive-text">Nama Guru</h5>
                <p class="responsive-text">Guru Mapel</p>
              </div>
            </div>
          </div>
        </div>
      </div>
  
      <!-- Daftar Guru BP / BK -->
      <div class="card card-guru mt-4">
        <h5 class="text-center mt-5">Daftar Guru BP / BK</h5>
        <div class="row mt-4 justify-content-center mb-5">
          <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card rounded-4 text-center">
              <div class="card-body">
                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="responsive-img">
                <h5 class="fw-semibold mt-4 responsive-text">Nama Guru</h5>
                <p class="responsive-text">Guru BP / BK</p>
              </div>
            </div>
          </div>
        </div>
      </div>
  
      <!-- Daftar Staf TU -->
      <div class="card card-guru mt-4">
        <h5 class="text-center mt-5">Daftar Staf TU</h5>
        <div class="row mt-4 justify-content-center mb-5">
          <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card rounded-4 text-center">
              <div class="card-body">
                <img src="~/assets/img/LOGO-SMK4.png" alt="img" class="responsive-img">
                <h5 class="fw-semibold mt-4 responsive-text">Nama Guru</h5>
                <p class="responsive-text">Staf TU</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  /* Font dan margin */
  h4, h5, p {
    font-family: "Poppins", serif;
  }
  
  h4 {
    margin-left: 95px;
  }
  
  .card-total {
    background-color: #1F60A0;
    text-align: center;
    color: #fff;
  }
  
  .card-total h5 {
    margin-top: 20px;
  }
  
  .card-total p {
    font-size: 15px;
  }
  
  .card-guru {
    width: 100%;
    margin: auto;
    text-align: center;
  }
  
  .responsive-img {
    width: 80px;
    height: auto;
    object-fit: contain;
  }
  
  .responsive-text {
    font-size: 1rem;
  }
  
  /* Media Queries untuk Responsivitas */
  @media (max-width: 768px) {
    h4 {
      margin-left: 15px;
      text-align: center;
    }
  
    .responsive-img {
      width: 60px;
    }
  
    .responsive-text {
      font-size: 0.9rem;
    }
  
    .card-body h5, .card-body p {
      font-size: smaller;
    }
  }
  
  @media (max-width: 576px) {
    h4 {
      font-size: 1.5rem;
    }
  
    .responsive-img {
      width: 50px;
    }
  
    .responsive-text {
      font-size: 0.8rem;
    }
  
    .card {
      margin-bottom: 15px;
    }
  
    .card-guru {
      width: 95%;
    }
  }
  </style>
  