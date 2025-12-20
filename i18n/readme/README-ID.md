![NekoUI](https://github.com/strivo-dev/nekoui-download/blob/main/assets/nekoui_banner.png)

<div align="center">

[![Github](https://img.shields.io/github/downloads/strivo-dev/nekoui-download/total?logo=github&labelColor=grat&color=black)](https://github.strivo.xyz/nekoui-download/releases)
[![Modrinth](https://img.shields.io/badge/dynamic/json?color=158000&label=downloads&prefix=+%20&query=downloads&url=https://api.modrinth.com/v2/project/EZpbRipP&logo=modrinth)](https://modrinth.com/mod/nekoui)
[![CurseForge](https://cf.way2muchnoise.eu/full_999428_downloads.svg)](https://www.curseforge.com/minecraft/mc-mods/neko-ui)
[![Enviroment](https://img.shields.io/badge/Enviroment-Client-purple)](https://modrinth.com/mod/nekoui)

[![License](https://img.shields.io/badge/License-ARR-green)](https://github.strivo.xyz/nekoui-download/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/strivo-dev/nekoui-download)](https://github.strivo.xyz/nekoui-download/issues)
[![Release](https://img.shields.io/badge/release-v1.0.3-blue)](https://modrinth.com/mod/nekoui/versions)
[![Crowdin](https://badges.crowdin.net/nekoui/localized.svg)](https://crowdin.com/project/nekoui)
[![Github Star](https://img.shields.io/github/stars/strivo-dev/nekoui-download)](https://github.strivo.xyz/nekoui-download)

</div>

Hadirkan pengalaman antarmuka pengguna (UI) yang segar di Minecraft dengan NekoUI dan latar belakang yang dapat disesuaikan untuk variasi tak terbatas.

****

> [!NOTE]
> Proyek ini tidak berafiliasi dengan, didukung oleh, atau terkait dengan game, perusahaan, atau merek pihak ketiga mana pun.

> [!TIP]
> Mencari README yang diterjemahkan? Anda dapat menemukannya [di sini](https://github.strivo.xyz/nekoui-download/tree/main/i18n/readme)

****

# Instalasi
Untuk memulai, unduh berkas mod .jar dari salah satu platform tepercaya atau sumber resmi di bawah ini.

### Platfrom Terpecaya
> - [CurseForge]
> - [Modrinth]

### Sumber Asli
> - [Website]

****

# Cara Menggunakan
> 1. Pindahkan file .jar yang telah diunduh ke folder mods Minecraft Anda:
> 2. Di Windows: C:\Users\<NamaAnda>\AppData\Roaming\.minecraft\mods
> 3. Di Linux/macOS: ~/.minecraft/mods
> 4. Pastikan Anda menggunakan mod loader yang kompatibel (Forge atau Fabric).
> 5. Jalankan game, dan NekoUI seharusnya sudah aktif!

### Menggunakan launcher custom?
> Jika Anda menggunakan MultiMC, Prism Launcher, GDLauncher, atau launcher kustom lainnya, cukup tambahkan mod ke folder mods instance, atau impor menggunakan pengelola mod bawaan launcher.

****

# Kompatibilitas  
NekoUI sangat berfokus pada kustomisasi antarmuka pengguna (UI), termasuk tata letak dan visual latar belakang. Akibatnya, **mod yang juga memodifikasi antarmuka pengguna Minecraft atau rendering latar belakang** dapat bertabrakan dengan NekoUI.  

Sumber ketidakkompatibilitas yang umum meliputi:
- Mod yang merombak atau mengganti menu utama atau elemen HUD.
- Mod terkait shader yang memodifikasi lapisan UI atau menerapkan pemrosesan pasca pada elemen 2D.
- Mod yang mengubah cara gambar latar belakang atau tekstur dimuat dan dirender.

Jika Anda mengalami masalah seperti elemen yang menimpa, latar belakang rusak, atau UI tidak tampil sesuai harapan, silakan periksa daftar mod Anda untuk potensi konflik dengan mod yang mengubah UI.

****

# Rekomendasi
Untuk meningkatkan pengalaman UI saat menggunakan NekoUI, sangat disarankan untuk menginstal **mod kustomisasi font** yang mengganti font default Minecraft.

Mod yang disarankan:
- [BetterFonts](https://www.curseforge.com/minecraft/mc-mods/betterfonts)
- [Smooth Font](https://www.curseforge.com/minecraft/mc-mods/smooth-font)
- [Caxton](https://modrinth.com/mod/caxton)
- Atau mod apa pun yang memungkinkan penggantian font default Minecraft dengan font bersih dan modern seperti **Poppins**, **Inter**, atau **Segoe UI**.

Penggunaan font modern akan secara signifikan meningkatkan keterbacaan dan konsistensi visual keseluruhan antarmuka yang disesuaikan oleh NekoUI.

****

# Versi yang didukung
| Versi Minecraft | Status | Versi NekoUI |
|-----------------|--------|--------------|
| 1.21.x          | stable | v1.0.3       |
| 1.20.x          | stable | v1.0.3       |

****

<details>
<summary><strong>FAQ (Pertanyaan yang Sering Diajukan)</strong></summary>

- **Mengapa latar belakang animasi tidak muncul?**
  - Latar belakang animasi tidak disertakan dalam mod karena ukuran file yang besar. Anda dapat mengunduhnya secara terpisah dari [NekoUI-Resources] atau [Han's Official Discord Server].

- **Saya sudah mengunduh latar belakang animasi, tetapi masih tidak muncul di layar judul. Mengapa?**
  - Pastikan Anda telah mengaktifkan paket sumber latar belakang di menu *Resource Packs*. Kemudian, buka layar konfigurasi mod untuk memilih latar belakang yang diinginkan.

- **Apa persyaratan sistem minimum untuk menjalankan mod ini dengan lancar?**
  - Kami merekomendasikan mengalokasikan setidaknya 4–6 GB RAM, dan menggunakan prosesor setara Intel Core i5 Generasi ke-8 atau lebih baik dengan GPU terintegrasi.

- **Di mana saya dapat melaporkan bug atau masalah?**
  - Silakan laporkan bug atau masalah di [Repositori GitHub NekoUI].

- **Apakah NekoUI kompatibel dengan mod UI atau shader lainnya?**
  - NekoUI bertujuan untuk kompatibel dengan sebagian besar mod, tetapi mod UI atau shader mungkin bertabrakan. Jika Anda menemukan masalah, coba nonaktifkan mod lain sementara atau laporkan konflik kepada kami.

- **Bagaimana cara mereset pengaturan NekoUI ke default?**
  - Anda dapat menghapus file konfigurasi NekoUI yang terdapat di folder `config/nekoui` dalam direktori Minecraft Anda.

- **Apakah NekoUI mendukung versi Minecraft yang lebih lama?**
  - Ya, tetapi pembaruan dirilis secara bertahap per versi. Jika versi Anda belum didukung, harap tunggu pembaruan mendatang.

</details>

****

# Kredit
> Terima kasih yang sebesar-besarnya kepada semua yang terlibat dalam pembuatan NekoUI:
> - nokarin (Pengembang Mod, Penguji Kode, Desainer Antarmuka Pengguna, Penerjemah, Penguji Mod)
> - Han's (Penemu, Penerjemah, Desainer Antarmuka Pengguna)
> - AetherLumine (Penerjemah)
> - howtoscriptinpython (Penerjemah untuk Rusia & Ukraina)
> - ExplerHD (Penguji Mod)
> - noxzym (Penguji Mod)
> - alfaruqi (Penerjemah untuk arab, brazil, mexico, italia, jerman, and georgia)

****

# Lisensi
```
NekoUI: Java Edition dilindungi hak cipta sepenuhnya
> © 2025 Han's Projects.
> © NekoUI: Java Edition 2025 - All Rights Reserved.
> © 2019-2025 Strivo Development - All Rights Reserved.
```

**Lihat peta jalan dan rencana kami di [sini](https://trello.com/b/mJA0DTKD)**

[CurseForge]: https://www.curseforge.com/minecraft/mc-mods/neko-ui
[Modrinth]: https://modrinth.com/mod/nekoui
[Website]: https://strivo.xyz/project/nekoui/download
