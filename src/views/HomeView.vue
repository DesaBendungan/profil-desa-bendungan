<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa Bendungan</p>
      <p class="text-lg font-semibold mt-4">Visi Desa Bendungan :</p>
      <p>Terwujudnya Masyarakat Desa Bendungan yang Berkeadaban, Maju, Nyaman dan Berkualitas dalam Kehidupan berlandaskan Nilai Agama, Sosial dan Budaya.</p>
      <p class="text-lg font-semibold mt-4">Misi Desa Bendungan :</p>
      <ul>
      <li>1. Mewujudkan Masyarakat yang Sehat, Peduli, Beradab dan Berkualitas; </li>
      <li>2. Menciptakan System Pemerintahan dan Perangkat Desa yang Aktif, Berkualitas dan Peduli dalam Melayani Masyarakat; </li>
      <li>3. Melaksanakan Pembangunan yang Merata, Berkelanjutan dan Berkualitas; </li>
      <li>4. Menjalin Kerjasama yang Harmonis dengan Mitra Desa, Lembaga Kemasyarakatan dan Lintas Sosial di Desa Bendungan; </li>
      <li>5. Menggali dan Meningkatkan Potensi dibidang Sumber Daya Alam dan Manusia demi Kesejahteraan Masyarakat. </li>
      </ul>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/struktur-desa-bendungan.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
