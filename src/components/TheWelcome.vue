<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Pendidikan</template>
    Saya, Mhd. Farhan Akbar Alhasbi, Seorang Mahasiswa dari <a href="https://uir.ac.id/" target="_blank" rel="UIR">Universitas
    Islam Riau</a>, Sebelumnya saya bersekolah di SMA NEGERI 1 BANGKO.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Jurusan</template>

    Fakultas yang saya ambil adalah Fakultas Teknik, Prodi Teknik Informatika,
     saat ini saya berada di semester 4 kelas B <a href="https://www.instagram.com/b1universe_?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank">b1universe</a>

    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon/>
    </template>
    <template #heading>Hobi</template>
    Berbicara tentang Hobi, selalu nya sebelum saya memasuki <a href="https://uir.ac.id" target="_blank">Universitas
    Islam Riau</a>, saya suka dengan aktifitas yang berbau seni seperti melukis dan menggambar, tetapi akhir akhir ini saya jarang bahkan
    bisa di bilang saya tidak pernah lagi melakukan hobi saya biasanya, di karenakan tugas di Fakultas Teknik yang sangat menumpuk
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Tempat Tanggal Lahir</template>

    Saya Lahir di Kabupaten <a href="https://rohilkab.go.id/pages/profil-kabupaten" target="_blank">Rokan Hilir,</a> Lebih tepatnya di Kota <a href="#">
    Bagansiapi Api,</a> Pada Tanggal 03 Oktober 2004

    </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Sosial Media</template>
    For more information click here! <br><a href="https://www.instagram.com/farhnakbar/">Instagram,</a><a href="#">Twitter</a>
    </WelcomeItem>
</template>
