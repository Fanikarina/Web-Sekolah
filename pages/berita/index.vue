<template>
  <div class="container">
    <div class="row">
      <div class="col d-flex justify-content-center items-center">
        <h2 class="text-white text-center">Berita SMK Negeri 4 Tasikmalaya</h2>
      </div>
    </div>
    <div class="garis text-white mt-5 mb-5">
      <h5 class="judul pt-2">Berita SMK Negeri 4 Tasikmalaya</h5>
    </div>
    <div class="galeri">
      <div class="row justify-content-center">
        <div class="col-3 mb-5">
          <div class="card rounded shadow">
            <img src="~/assets/img/Expo.webp" class="card-img-top" alt="..." />
            <div class="card-body m-3">
              <a
                href="https://radartasik.id/2023/03/02/siswa-smkn-4-tasikmalaya-adu-inovasi-dan-kreativitas-di-expo-creanova/"
                ><h6 class="text-center">
                  Siswa SMKN 4 Tasikmalaya Adu Inovasi dan Kreativitas di Expo
                  Creanova
                </h6>
              </a>
            </div>
          </div>
        </div>
        <div class="col-3 mb-5">
          <div class="card rounded shadow">
            <img src="~/assets/img/honda.jpeg" class="card-img-top" alt="..." />
            <div class="card-body m-3">
              <a
                href="https://otomotifzone.com/sinergi-bagi-negeri-dam-jalin-kerjasama-dengan-smkn-4-tasikmalaya-terapkan-kurikulum-teknik-bisnis-sepeda-motor-honda/"
                ><h6 class="text-center">
                  DAM Jalin Kerjasama Dengan SMKN 4 Tasikmalaya Terapkan
                  Kurikulum TBSM Honda
                </h6>
              </a>
            </div>
          </div>
        </div>
        <div class="col-3 mb-5">
          <div class="card rounded shadow">
            <img src="~/assets/img/job-fair.jpg" class="card-img-top" alt="..." />
            <div class="card-body m-3">
              <a
                href="https://radartasik.id/2023/10/12/smkn-4-tasikmalaya-koneksikan-iduka-dengan-pencari-kerja/#google_vignette"
                ><h6 class="text-center">
                    SMKN 4 Tasikmalaya Koneksikan Iduka dengan Pencari Kerja
                </h6>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  max-width: 100%;
}

.col {
  background-image: url("~/assets/img/bg-artikel.png");
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 250px;
  width: 100%;
  display: flex;
  align-items: center;
  margin: auto;
}
.card {
  margin: auto;
}
h1,h2,h3,h4,h5,h6,p {
  font-family: "Poppins", serif;
  margin: auto;
}
.garis {
  background-color: #151e2c;
  height: 40px;
}
.judul {
  margin-left: 2%;
}
a {
  color: black !important;
  text-decoration: none;
}
</style>
