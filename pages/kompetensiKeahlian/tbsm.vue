<template>
  <div class="container">
    <div class="row">
      <div class="col d-flex justify-content-center items-center">
        <h2 class="text-white text-center">Teknik dan Bisnis Sepeda Motor</h2>
      </div>
    </div>
    <div class="layer mt-5 mb-5">
      <div class="row">
        <div class="card d-flex shadow rounded">
          <img src="~/assets/img/bg-tsm.png" alt="" class="tsm mt-3" />
          <h3 class="mt-5">Apa itu Teknik dan Bisnis Sepeda Motor?</h3>
          <div class="card-body">
            <p>
              Teknik dan Bisnis Sepeda Motor (TBSM) adalah salah satu cabang
              ilmu teknik mesin yang mempelajari tentang bagaimana merancang,
              membuat dan mengembangkan alat-alat transportasi darat yang
              menggunakan mesin, terutama sepeda motor.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="kaprog">
      <div class="card shadow mb-5 d-flex justify-content-center">
        <div class="row">
          <div class="col-md-4 kepsek">
            <img
              src="~/assets/img/logo.png"
              class="img-fluid rounded-start"
              alt="..."
            />
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h5 class="card-title">Fani S.Pd, M.Pd</h5>
              <p class="card-text">Kepala Program TBSM</p>
              <hr />
              <p class="card-text">
                <medium class="text-muted">Assalamu'alaikum Wr, Wb</medium>
              </p>
              <p class="card-text">
                <medium class="text-muted"
                  >Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                  Quasi tempore, repudiandae deleniti molestias ipsum magnam
                  eveniet sapiente in. Quibusdam perspiciatis ducimus alias
                  officia et eos. Magni labore accusamus reprehenderit. Lorem
                  ipsum dolor, sit amet consectetur adipisicing elit. Reiciendis
                  odit porro dolor sint eos magni sequi! Inventore iste unde
                  fuga debitis alias eos est, odit vel. Repudiandae cupiditate
                  sit eos! lore <ad class="lore"></ad
                ></medium>
              </p>
              <p class="card-text">
                <medium class="text-muted">Wassalamu'alaikum Wr, Wb</medium>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="judul mt-5 mb-5 text-white text-center">
      <h3 class="py-1">Galeri</h3>
    </div>
    <div class="row mt-3 mb-5 justify-content-center m-3">
      <div class="col-4">
        <div class="card">
          <img src="~/assets/img/tsm-asta.jpg" alt="img" class="card-img-top" />
        </div>
      </div>
      <div class="col-4">
        <div class="card">
          <img src="~/assets/img/tsm-asta.jpg" alt="img" class="card-img-top" />
        </div>
      </div>
      <div class="col-4">
        <div class="card">
          <img src="~/assets/img/tsm-asta.jpg" alt="img" class="card-img-top" />
        </div>
      </div>
    </div>
  </div>
  <div class="mt-5"></div>
  <div class="row mt-3 mb-5 justify-content-center m-3">
    <div class="col-4">
      <div class="card">
        <img src="~/assets/img/slr.jpeg" alt="img" class="card-img-top" />
      </div>
    </div>
    <div class="col-4">
      <div class="card">
        <img src="~/assets/img/slr.jpeg" alt="img" class="card-img-top" />
      </div>
    </div>
    <div class="col-4">
      <div class="card">
        <img src="~/assets/img/slr.jpeg" alt="img" class="card-img-top" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  max-width: 100%;
}

.col {
  background-image: url("~/assets/img/tsm.png");
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
  margin-top: 7%;
  width: 80%;
}
.tsm {
  width: 12%;
}
.img-fluid {
  width: 100%;
}
.card {
  width: 80%;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.judul {
  background-color: #151e2c;
  height: 50px;
}
.card {
  height: 77%;
}
h1,h2,h3,h4,h5,h6,p {
  font-family: "Poppins", serif;
  margin: auto;
}

h4 {
  margin-left: 95px;
}

.card-big,
hr {
  width: 85%;
  margin: auto;
}
</style>
