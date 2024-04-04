<script setup lang="ts">
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
    <template #heading>Tentang</template>
    Nama lengkap saya adalah Lara Aulia Putri, dan tempat kelahiran saya adalah Kajai, sebuah kota kecil yang terletak di Sumatera Barat, Indonesia, saya lahir pada tanggal 18 November 2003. Saat ini, saya tengah meniti perjalanan pendidikan sebagai seorang mahasiswi di Universitas Islam Riau, yang terletak di Jalan Kaharuddin Nst, Pekanbaru. Saya telah menjalani perjalanan pendidikan ini selama beberapa waktu dan saat ini berada di semester keempat. Di universitas ini, saya mengambil jurusan Teknik Informatika, yang telah menarik minat dan perhatian saya sejak awal. Berada di lingkungan akademik ini memberikan saya kesempatan untuk belajar dan berkembang di bidang yang saya minati, serta bertemu dengan berbagai orang yang berbagi minat dan aspirasi yang sama.
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>
Riwayat pendidikan saya :
<li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/8ba5d3d9-e742-4187-b455-fcc2570a9350" target="_blank" rel="noopener">TK ABA </a></li>

      <li><a href="https://dapo.kemdikbud.go.id/sekolah/2F646F92D4CD877DC112" target="_blank" rel="noopener">SD 16 Talamau</a></li>
      <li><a href="https://dapo.kemdikbud.go.id/sekolah/D5F1A3D7906B1D92C787" target="_blank" rel="noopener">SMPN 02 Talamau</a></li>
      <li><a href="https://madrasah.kemenag.go.id/kelembagaan/web/profile?nsm=131113120004&provinsi=13&kota=1312" target="_blank" rel="noopener">MAN 04 Pasaman Barat</a></li>
      <li><a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a></li>

  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skill</template>
    Kemampuan merupakan kunci keberhasilan dalam berkomunikasi, bekerja sama, dan menyesuaikan diri di lingkungan profesional.    <ul>
      <li>Mysql</li>
      <li>Database</li>
      <li>Jaringan</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Pengalaman</template>
    Saya tidak akan menyia-nyiakan peluang untuk belajar dan berkembang dari setiap pengalaman yang saya jalani    <ul>
    <li>Anggota Osis</li>
      <li>Marching band</li>
</ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Sosial Media</template>
Saya lumayan aktif di sosial media seperti Instagram, berikut adalah Instagram saya
   :<a href="https://www.instagram.com/_laraaulia" target="_blank">_laraaulia</a>
  </WelcomeItem>
</template>