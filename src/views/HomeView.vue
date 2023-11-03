<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Membangun Bersama Masyarakat yang Amanah, Jujur, Adil dan Transparan melalui Peningkatan Sumber Daya Manusia, Pengelolaan Sumber Daya Alam dengan AkhlakulKarimah”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Meningkatkan Profesionalisme Pelayanan Publik;
          <ul>
            <li>Meningkatkan kualitas pelayanan masyarakat dan penyelenggaraan pemerintahan desa; </li>
            </ul>
        </li>
        <li>
          2. Meningkatkan Kesehatan masyarakat melalui Program Pemerintah;
        </li>
        <li>
          3. Mewujudkan sarana dan prasarana infrastruktur yang nyaman;
        </li>
        <li>
          4. Mewujudkan kesadaran masyarakat terhadap pentingnya pendidikan;
        </li>
        <li>
          5.Mewujudkan masyarakat yang agamis dan mandiri;
        </li>
        <li>
        </li>
        <li>
        </li>
        <li>
        </li>
        <li>
        </li>
        <li>
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
