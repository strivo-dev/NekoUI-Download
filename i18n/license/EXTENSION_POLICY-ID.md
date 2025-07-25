# Kebijakan Ekstensi NekoUI
Dokumen ini menjelaskan kebijakan terkait **ekstensi eksternal** dalam proyek NekoUI, khususnya aset latar belakang untuk NekoUI: Java Edition dan NekoUI: Bedrock Edition.

---

## Ringkasan
NekoUI mendukung **latar belakang kustom eksternal** (statis atau animasi) melalui sistem paket sumber daya yang fleksibel.  
Ekstensi latar belakang ini **bukan bagian dari mod inti** dan dapat dibuat, dimodifikasi, dan dibagikan secara independen.

---

## Aturan Komunitas
- **Latar belakang NSFW** atau konten yang bersifat seksual, kekerasan, atau tidak pantas lainnya **dilarang keras** di komunitas resmi NekoUI (Discord, forum, dll.).
- Anda dapat menggunakan konten tersebut **hanya untuk penggunaan pribadi**, atau **membagikannya secara pribadi atau di luar komunitas resmi**.

---

## NekoUI: Bedrock Edition
### 1. Latar Belakang Default
- Secara default, Bedrock Edition menggunakan background paranoma minecraft.
- Tidak ada latar belakang pihak ketiga, berbasis franchise, atau berhak cipta yang disertakan.

### 2. Dukungan Latar Belakang Eksternal
- Latar belakang eksternal harus mengikuti struktur yang didefinisikan dalam [panduan ini](https://discord.com/channels/1214492329046581278/1396857398857302217/1396857398857302217).
- Jumlah frame dibatasi hingga **100 frame** dengan nama file seperti `hans_common_100.png`.

### 3. Batasan Modifikasi
Dilarang keras untuk memodifikasi file-file inti berikut:
- Semua file di dalam `.hans_common_files`, kecuali:
- `hans_animated_background.json`  
  - `hans_loading_background.json`
- Semua file di `hans_common_files_experimental`

Jika Anda memiliki modifikasi sendiri dengan kode Anda sendiri, disarankan untuk menggunakan bagian `modifications`: `{}` di dalam ekstensi Anda, dan letakkan di bawah:
- Folder `ui/`
- Atau folder lain yang secara eksplisit ditandai sebagai dapat dimodifikasi

Tidak ada batasan untuk memodifikasi:  
- Tekstur UI  
- Font  
- Elemen estetika non-inti lainnya  

---  

## NekoUI: Java Edition  
### 1. Latar Belakang Default
- Mod ini hanya menyertakan latar belakang statis hitam solid secara default.
- Tidak ada materi pihak ketiga atau berhak cipta.

### 2. Dukungan Latar Belakang Eksternal
- Latar belakang kustom harus mengikuti struktur folder ini:  
  `assets/nekoui/background/<name>/`
- Latar belakang animasi harus berisi file frame berurutan (misalnya, `frame0.png`, `frame1.png`, dll.).
- Tidak ada **batasan frame**, tetapi kinerja sistem dapat bervariasi tergantung pada jumlah dan resolusi frame.

---

## Izin
Anda **diizinkan untuk**:
- Membuat dan berbagi paket latar belakang Anda sendiri.
- Memodifikasi atau meremix latar belakang tidak resmi.
- Mendistribusikan paket latar belakang Anda secara publik (misalnya di GitHub, Modrinth, CurseForge).

Anda **tidak diizinkan untuk**:
- Mendistribusikan ulang mod NekoUI atau kode yang dikompilasi bersama latar belakang Anda.
- Mengklaim ekstensi Anda sebagai “resmi” atau didukung oleh tim NekoUI.
- Menggunakan aset komersial dalam latar belakang Anda kecuali Anda sepenuhnya memiliki atau memiliki lisensi untuk menggunakannya.

---

## Pernyataan Penolakan
- Penulis (`nokarin`) **tidak bertanggung jawab** atas ekstensi pihak ketiga, latar belakang yang dikirimkan pengguna, atau pelanggaran hak kekayaan intelektual.
- Pengguna sepenuhnya bertanggung jawab untuk mematuhi undang-undang hak cipta dan kekayaan intelektual yang berlaku.

---

Dengan menggunakan atau membuat ekstensi untuk NekoUI, Anda setuju dengan kebijakan ini.  
Untuk pengiriman, pameran, atau pertanyaan, silakan hubungi Penulis atau bergabung dengan server Discord resmi NekoUI.