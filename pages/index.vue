<template>
    <div class="container-fluid p-0">

<!-- Carousel -->
        <!-- <div class="carousel bg-light py-5 text-center">
            <div class="row justify-content-center">
                <div class="col-lg-8 col-md-10 col-sm-12">
                    <h1>Selamat datang di Website Resmi</h1>
                    <h1 class="mt-2 fw-bold">SMK Negeri 4 Tasikmalaya</h1>
                </div>
            </div>
        </div> -->
        <div class="carousel bg-light py-5 text-center position-relative">
            <div class="text-overlay">
                <h1>Selamat datang di Website Resmi</h1>
                <h1 class="mt-2 fw-bold">SMK Negeri 4 Tasikmalaya</h1>
            </div>
        </div>


<!-- Sambutan -->
        <div class="card bg-light text-black mt-5">
            <div class="container py-5">
                <!-- <h4 class="text-center">Sambutan <br> <span class="text-primary">Kepala Sekolah</span></h4>
                <div class="row mt-4 align-items-center">
                    <div class="col-lg-6 col-md-6 col-sm-12 mb-4">
                        <h3>Kurniawan S.Pd, M.Pd</h3>
                        <p class="mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. In molestiae natus cumque odit doloremque atque a iste? Dolor iure eius asperiores nobis eum modi in perferendis, libero, expedita facilis repellendus?</p>
                        <p class="mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. In molestiae natus cumque odit doloremque atque a iste? Dolor iure eius asperiores nobis eum modi in perferendis, libero, expedita facilis repellendus?</p>
                    </div>
                    <div class="col-lg-6 col-md-6 col-sm-12">
                        <div class="card bg-primary p-3 mx-auto" style="max-width: 275px;">
                            <img src="../assets/img/kurniawan.png" class="card-img-top rounded-3" alt="Kepala Sekolah">
                        </div>
                    </div>
                </div> -->
                <div class="row pt-5">
                    <div class="jumbotron text-center">
                        <img src="/assets/img/kurniawan.png" width="200px" class="rounded-circle img-thumbnail" />
                            <h1 class="name">Kurniawan S.Pd, M.Pd</h1>
                                <h4 class="kepsek pt-4">Kepala SMK Negeri 4 Tasikmalaya</h4>
                                    <p class="lead">terwujudnya lulusan yang cerdas, kompetitif, adaptif, produktif, dan ber imtak</p>
                    </div>
                </div>
            </div>
        </div>

<!-- Konsentrasi Keahlian -->
<div class="container mt-5">
    <h4>Konsentrasi <br> <span class="text-primary">Keahlian</span></h4>
    <div class="row mt-4 g-4">
        <!-- Loop over cards -->

        <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="card rounded-4 text-center">
                <div class="card-body">
                    <img src="../assets/img/tjkt.png" alt="TJKT" class="mt-3 mb-3" style="max-height: 100px;">
                    <h5 class="fw-semibold">TJKT</h5>
                    <p>Teknik Jaringan, Komputer dan Telekomunikasi</p>
                </div>
            </div>
        </div>

        <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="card rounded-4 text-center">
                <div class="card-body">
                    <img src="../assets/img/pplg.png" alt="PPLG" class="mt-3 mb-3" style="max-height: 100px;">
                    <h5 class="fw-semibold">PPLG</h5>
                    <p>Pengembangan Perangkat Lunak dan Gim</p>
                </div>
            </div>
        </div>

        <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="card rounded-4 text-center">
                <div class="card-body">
                    <img src="../assets/img/tbsm.png" alt="TBSM" class="mt-3 mb-3" style="max-height: 100px;">
                    <h5 class="fw-semibold">TBSM</h5>
                    <p>Teknik dan Bisnis Sepeda Motor</p>
                </div>
            </div>
        </div>

        <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="card rounded-4 text-center">
                <div class="card-body">
                    <img src="../assets/img/dkv.png" alt="DKV" class="mt-3 mb-3" style="max-height: 100px;">
                    <h5 class="fw-semibold">DKV</h5>
                    <p>Desain Komunikasi Visual</p>
                </div>
            </div>
        </div>
        
        <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="card rounded-4 text-center">
                <div class="card-body">
                    <img src="../assets/img/toi.png" alt="TOI" class="mt-3 mb-3" style="max-height: 100px;">
                    <h5 class="fw-semibold">TOI</h5>
                    <p>Teknik Otomasi Industri</p>
                </div>
            </div>
        </div>

    </div>
</div>

<!-- Artikel -->
<!-- <div class="container mt-5">
    <h4>Artikel <br> <span class="text-primary">Terbaru</span></h4>
    <p class="mt-3">Berita terbaru, cerita inspiratif, dan informasi terkini seputar kegiatan serta prestasi sekolah kami.</p>
    <div class="row mt-4 g-4">
        <div class="col-lg-5 col-md-6 col-sm-12">
            <div class="card rounded-4">
                <img src="../assets/img/school.jpeg" class="card-img-top p-2 rounded-4" alt="Artikel">
                <div class="card-body">
                    <p class="text-end">20 Desember 2024</p>
                    <h5 class="text-center mt-1">SMKN 4 Tasikmalaya Koneksikan Iduka dengan Pencari Kerja</h5>
                    <p class="mt-4">Baca Selengkapnya <i class="bi bi-arrow-right-circle text-black"></i></p>
                </div>
            </div>
        </div>
        <div class="col-lg-5 col-md-6 col-sm-12">
            <div class="card rounded-4">
                <img src="../assets/img/school.jpeg" class="card-img-top p-2 rounded-4" alt="Artikel">
                <div class="card-body">
                    <p class="text-end">20 Desember 2024</p>
                    <h5 class="text-center mt-1">SMKN 4 Tasikmalaya Koneksikan Iduka dengan Pencari Kerja</h5>
                    <p class="mt-4">Baca Selengkapnya <i class="bi bi-arrow-right-circle text-black"></i></p>
                </div>
            </div>
        </div>
    </div>
    <div class="text-center mt-5">
        <button class="btn btn-primary shadow">Artikel Lainnya</button>
    </div>
</div> -->
<div class="container mt-5">
    <div class="row justify-content-center">
        <div class="col-lg-6 col-md-8 col-sm-12 text-center">
            <h5 class="text-dark">Alamat</h5>
            <hr>
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3957.2131636317426!2d108.25189907404213!3d-7.32993997208793!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e6f59eeb6bda36f%3A0xa9e724a275da6c2d!2sSMK%20Negeri%204%20Tasikmalaya!5e0!3m2!1sid!2sid!4v1734660682140!5m2!1sid!2sid" 
                class="w-100 rounded"
                height="350" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade">
            </iframe>
        </div>
    </div>
</div>
                

        
    </div>
</template>

<style scoped>
.carousel {
    background-image: url('../assets/img/bgHome.png');
    background-size: cover;
    background-position: center;
    height: 500px;
    position: relative; 
    width: 100%;
}    
/* .col {
    padding: 0;
}

.text {
    margin-left: 100px;
    margin-right: 0;
} */
.text-overlay {
    position: absolute; /* Posisi absolut di dalam elemen carousel */
    top: 50%; /* Tempatkan di tengah secara vertikal */
    left: 50%; /* Tempatkan di tengah secara horizontal */
    transform: translate(-50%, -50%); /* Koreksi agar benar-benar di tengah */
    text-align: center; /* Teks rata tengah */
    color: white; /* Warna teks */
}
h1 {
    
    background-color: #1F60A0;
    color: #ffff;
    font-family: "Poppins", serif;
    padding: 10px 20px; /* Ruang di dalam elemen teks */
    border-radius: 8px;
    /* margin-top: 100px;
    width: fit-content;
    text-align: center; Tambahkan properti ini
    margin-left: auto;  Tambahkan properti ini
    margin-right: auto; Tambahkan properti ini */

}

h6, h5, h4, h3, p, .btn {
    font-family: "Poppins", serif;

}

h5 {
    color: #ffff;
    margin-top: 120px;
}

i {
    color: #ffff;
    margin-top: 120px;
    margin-left: 10px;
}

.info {
    margin-left: 100px;
}

img {
    width: 200px;
}

h4 {
    margin-left: 95px;
}

.card-img {
    height: 300px;
    width: 80%;
    margin-left: 70px;
}

.card-img img {
    width: 95%;
    margin-bottom: 40px;
}

.card-item .card {
    width: 70%;
    height: 200px;
}

.flex-container {
    display: flex;
    flex-direction: column;
    gap: 20px; /* Space between rows */
}

.flex-container .row {
    display: flex;
    justify-content: center;
    gap: 20px; /* Space between cards */
}


.flex-container .card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 1px solid #ffff;
    /* padding: 20px; */
    text-align: center;
    flex: 1; /* Cards take equal space */
    max-width: 25%; /* Adjust card width */
}

.card-body h5 {
    margin-top: 30px;
    color: #000;
}

.card-body p {
    font-size: 15px;
}

.card-body img {
    width: 80px;
}

.text-artikel p {
    margin-left: 95px;
    max-width: 30%;
}

.card-img-top {
    width: 100%;
    height: 250px;
}

.artikel .card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 2px solid #ffff;
}

</style>