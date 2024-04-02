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
    <template #heading>Profil</template>

    Saya Syifa Nur Medina lahir di Pekanbaru, 22 Januari 2003 sebagai seseorang 
    yang ingin mempelajari dunia IT. Saya menyukai jurusan saya sebagai mahasiswa
    teknik informatika di
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>
    <br>Saya mempunyai target lulus kuliah 3.5 tahun (amin) 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    Pendidikan saya:
  <ul>
  <br> 2009-2015 
    <li><a href="" target="_blank" rel="noopener">Sekolah Dasar Negeri 002 Pekanbaru</a></li>
  <br> 2015-2018
    <li><a href="https://smpn16pekanbaru.sch.id/" target="_blank" rel="noopener">Sekolah Menengah Pertama Negeri 16 Pekanbaru</a></li>
  <br> 2018-2021 
    <li><a href="https://sman7pekanbaru.sch.id/" target="_blank" rel="noopener">Sekolah Menengah Atas Negeri 7 Pekanbaru</a></li>
  <br> 2022-sekarang 
    <li><a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a></li>

    <br />
  </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman Organisasi</template>

    Organisasi yang pernah saya ikuti:
    <ul>
    <li><a href="https://www.instagram.com/passus_sman7_pekanbaru?igsh=a2J4YTRjbmducG4z" target="_blank" rel="noopener">PASKIBRA (SMA)</a></li>
    <li><a href="https://www.instagram.com/osissman7pku?igsh=MTlzNWQ5MTd5emo0Mw==" target="_blank" rel="noopener">OSIS (SMA)</a></li>
    <li><a href="" target="_blank" rel="noopener">ANGGOTA KPPS</a></li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Kontak Saya</template>

    Kontak dan Media sosial saya: 
    <br> Instagram
    <a href="https://www.instagram.com/ssyifanm_?igsh=N280dXhxcjg1Nzl2" target="_blank" rel="noopener">ssyifanm_</a>
    <br> Spotify
    <a href="https://open.spotify.com/user/31hpa4hwooeojtqhlaoqyt7f5d54?si=UNw58hSrTuCH6oWQi662ng" target="_blank" rel="noopener">Iris</a>
    <br> WhatsApp
    <a href="" target="_blank" rel="noopener">+628238410xxxx</a>
    <br> Email
    <a href="" target="_blank" rel="noopener">irishollyhock0@gmail.com</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hobby</template>

    <ul>
    <li> melakukan kegiatan yang positif </li>
    <li> mendengar musik </li>
    </ul>
  </WelcomeItem>
</template>
