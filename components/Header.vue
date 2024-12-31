<template>
  <div class="container row">
    <div class="col-12 d-flex justify-content-end">
      <p class="text-white py-1">
        "SMK BISA, SMK HEBAT" | {{ curr_date }}</p>
    </div>
  </div>
</template>

<style scoped>
.container {
  background-color: #151e2c;
  max-width: 100%;
  height: 35px;
  margin: 0;
}
</style>

<script setup>

  let hari = ["Minggu", "Senin", "Selasa", "Rabu", "Kamis", "Jumat", "Sabtu"];
  let bulan = [
    "Januari",
    "Februari",
    "Maret",
    "April",
    "Mei",
    "Juni",
    "Juli",
    "Agustus",
    "September",
    "Oktober",
    "November",
    "Desember",
  ];
  let tanggal = new Date().getDate();
  let _hari = new Date().getDay();
  let _bulan = new Date().getMonth();
  let _tahun = new Date().getFullYear();

  hari = hari[_hari];
  bulan = bulan[_bulan];

  // tahun = _tahun < 1000 ? _tahun + 1900:
  // return hari + "," + tanggal + "" + bulan + "" + _tahun;  
  let curr_date = hari + ", " + tanggal + " " + bulan + " " + _tahun;

</script>
