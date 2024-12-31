<template>
  <div class="container">
    <div class="row">
      <div class="col d-flex justify-content-center items-center">
        <h2 class="text-white text-center">Data Staf Pengajar / Guru</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-12 d-flex justify-content-center mt-5">
        <div class="card shadow" style="width: 15rem">
          <div class="card-body">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="50"
              height="50"
              fill="white"
              class="bi bi-people-fill"
              viewBox="0 0 16 16"
            >
              <path
                d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6m-5.784 6A2.24 2.24 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.3 6.3 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1zM4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5"
              />
            </svg>
            <h5 class="text-center text-white">82 Orang</h5>
            <p class="card-text text-center text-white">
              Total Guru / Pendidik
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-6 mt-5 mb-5">
        <div class="card shadow" style="width: 15rem">
          <div class="card-body">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="50"
              height="50"
              fill="white"
              class="bi bi-person-standing"
              viewBox="0 0 16 16"
            >
              <path
                d="M8 3a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3M6 6.75v8.5a.75.75 0 0 0 1.5 0V10.5a.5.5 0 0 1 1 0v4.75a.75.75 0 0 0 1.5 0v-8.5a.25.25 0 1 1 .5 0v2.5a.75.75 0 0 0 1.5 0V6.5a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3v2.75a.75.75 0 0 0 1.5 0v-2.5a.25.25 0 0 1 .5 0"
              />
            </svg>
            <h5 class="text-center text-white">82 Orang</h5>
            <p class="card-text text-center text-white">Laki-laki</p>
          </div>
        </div>
      </div>
      <div class="col-6 mt-5">
        <div class="card shadow" style="width: 15rem">
          <div class="card-body">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="50"
              height="50"
              fill="white"
              class="bi bi-person-standing-dress"
              viewBox="0 0 16 16"
            >
              <path
                d="M8 3a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3m-.5 12.25V12h1v3.25a.75.75 0 0 0 1.5 0V12h1l-1-5v-.215a.285.285 0 0 1 .56-.078l.793 2.777a.711.711 0 1 0 1.364-.405l-1.065-3.461A3 3 0 0 0 8.784 3.5H7.216a3 3 0 0 0-2.868 2.118L3.283 9.079a.711.711 0 1 0 1.365.405l.793-2.777a.285.285 0 0 1 .56.078V7l-1 5h1v3.25a.75.75 0 0 0 1.5 0Z"
              />
            </svg>
            <h5 class="text-center text-white">29 Orang</h5>
            <p class="card-text text-white text-center">Perempuan</p>
          </div>
        </div>
      </div>
    </div>
    <div class="row mt-5">
      <div class="guru">
        <div class="row layer mt-5">
          <div class="judul text-center mt-5">
            <h4 class="card-title">Guru / Pendidik</h4>
            <p class="card-text">
              <small class="text-muted">SMK Negeri 4 Tasikmalaya</small>
            </p>
          </div>
          <div v-for="(guru, i) in gurus" :key="i" class="col-3 p-3">
            <div class="card">
              <img :src="guru.foto" alt="" />
              <h6 class="text-center p-3">{{ guru.nama }}</h6>
              <p>{{ guru.mapel }}</p>
            </div>
          </div>
        </div>
      </div>
      <div class="guru2">
        <div class="row layer2 mt-5">
          <div class="judul text-center text-white mt-5">
            <h4 class="card-title">Guru BP / BK</h4>
            <p class="card-text">
              <small class="text-white">SMK Negeri 4 Tasikmalaya</small>
            </p>
          </div>
          <div class="col-2">
            <div class="card">
              <img src="~/assets/img/logo.png" alt="" />
            </div>
          </div>
          <div class="col-2">
            <div class="card">
              <img src="~/assets/img/logo.png" alt="" />
            </div>
          </div>
          <div class="col-2">
            <div class="card">
              <img src="~/assets/img/logo.png" alt="" />
            </div>
          </div>
          <div class="col-2">
            <div class="card">
              <img src="~/assets/img/logo.png" alt="" />
            </div>
          </div>
          <div class="col-2">
            <div class="card">
              <img src="~/assets/img/logo.png" alt="" />
            </div>
          </div>
          <div class="col-2">
            <div class="card">
              <img src="~/assets/img/logo.png" alt="" />
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
  background-image: url("~/assets/img/smk negeri.jpg");
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 250px;
  width: 100%;
  display: flex;
  align-items: center;
  margin: auto;
}

.card .card-body {
  background-color: #151e2c;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  border-radius: 3%;
}

.col-6 {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.guru {
  background-color: #151e2c;
  width: 100%;
  padding-bottom: 3rem;
}
.guru2 {
  background-color: #ffffff;
  width: 100%;
  padding-bottom: 3rem;
}

.layer {
  background-color: #ffff;
  width: 95%;
  margin: auto;
}
.layer2 {
  background-color: #151e2c;
  width: 95%;
  margin: auto;
}

.card {
}
h1,
h2,
h3,
h4,
h5,
h6,
p {
  font-family: "Poppins", serif;
  margin: auto;
}
</style>

<script setup>
const supabase = useSupabaseClient();
const gurus = ref([]);

const getGuru = async () => {
  const { data, error } = await supabase.from("guru").select();
  if (data) {
    gurus.value = data;
    data.forEach((guru) => {
      const { data } = supabase.storage
        .from("fotoGuru")
        .getPublicURL(guru.foto);
      if (data) {
        guru.foto = data.publicURL;
      }
    });
    console.log(error);
  }
};
onMounted(() => {
  getGuru();
});
</script>
