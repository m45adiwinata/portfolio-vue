<script setup lang="ts">
  import { RouterLink } from 'vue-router'
  import 'bootstrap/dist/css/bootstrap.css'
  import Profile from '../src/components/Profile.vue'
  import Navbar from '../src/components/Navbar.vue'
</script>

<template>
  <Navbar />
  <div class="row">
    <div class="col-md-4"></div>
    <div class="col-md-4 text-center">
      <Profile />
    </div>
    <div class="col-md-4"></div>
  </div>
  <div class="row">
    <div class="col-md-12 text-center mt-3">
      <h4>My Projects</h4>
    </div>
    <div class="col-md-4">
      <div class="card-body">
        <img src="/rb.png" class="card-img-top" alt="siajaib">
        <div class="card-body">
          <h5>Reformasi Birokrasi</h5>
          <p>Website berita Pemkab Buleleng</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card-body">
        <img src="/siajaib.png" class="card-img-top" alt="siajaib">
        <div class="card-body">
          <h5>SiAjaib</h5>
          <p>Sistem pengajuan perizinan online Kabupaten Buleleng</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card-body">
        <img src="/virendra.png" class="card-img-top" alt="siajaib">
        <div class="card-body">
          <h5>Wahana Virendra</h5>
          <p>Sistem tiketing penyebrangan kapal Pelabuhan Padang Bai</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>
