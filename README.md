<p align="center">
  <img src="assets/banner.png" alt="Arus! Download Manager" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/baharida/arus-download-manager/releases/latest">
    <img src="https://img.shields.io/github/v/release/baharida/arus-download-manager?style=flat-square&color=13795B&label=Latest%20Release" alt="Latest Release" />
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(x64)-0F6E52?style=flat-square" alt="Windows 10/11 x64" />
  <img src="https://img.shields.io/badge/Installer-Full%20Offline-178766?style=flat-square" alt="Full Offline Installer" />
  <a href="https://chromewebstore.google.com/detail/mdidagnhjbilkgbafhchnghoflbakfmk">
    <img src="https://img.shields.io/badge/Chrome%20Web%20Store-Manifest%20V3-1E6B52?style=flat-square" alt="Chrome Web Store Extension" />
  </a>
  <a href="https://addons.mozilla.org/firefox/addon/arus-download-manager/">
    <img src="https://img.shields.io/badge/Firefox%20Add--ons-Manifest%20V3-FF7139?style=flat-square" alt="Firefox Add-ons Extension" />
  </a>
  <a href="https://github.com/baharida/arus-download-manager/releases/latest">
    <img src="https://img.shields.io/github/downloads/baharida/arus-download-manager/total?style=flat-square&color=0D9488&label=Downloads" alt="Total Downloads" />
  </a>
</p>

<p align="center">
  <strong>Arus! Download Manager</strong> adalah aplikasi manajer unduhan native untuk Windows (64-bit) yang menggabungkan akselerasi HTTP/HTTPS multi-segmen, dekripsi cloud native, pengunduh video/audio &amp; galeri 65+ platform, konverter media offline, klien BitTorrent/Magnet, serta integrasi ekstensi browser resmi untuk ekosistem <strong>Chromium</strong> maupun <strong>Firefox</strong> dalam satu paket instalasi mandiri.
</p>

<p align="center">
  <a href="https://github.com/baharida/arus-download-manager/releases/latest">
    <img src="https://img.shields.io/badge/Download%20untuk%20Windows%20(64--bit)-13795B?style=for-the-badge" height="38" alt="Download Arus! untuk Windows (64-bit)" />
  </a>
  &nbsp;
  <a href="https://chromewebstore.google.com/detail/mdidagnhjbilkgbafhchnghoflbakfmk">
    <img src="https://img.shields.io/badge/Chrome%20%2F%20Edge%20%2F%20Brave-242C38?style=for-the-badge" height="38" alt="Ekstensi Chrome Web Store" />
  </a>
  &nbsp;
  <a href="https://addons.mozilla.org/firefox/addon/arus-download-manager/">
    <img src="https://img.shields.io/badge/Firefox%20%2F%20Zen%20%2F%20Floorp-FF7139?style=for-the-badge" height="38" alt="Ekstensi Mozilla Firefox Add-ons" />
  </a>
</p>

---

## Tampilan Antarmuka

Antarmuka mendukung tema terang (*Light Mode*) dan gelap (*Dark Mode*), pilihan Bahasa Indonesia dan Inggris yang tersinkronisasi otomatis dengan ekstensi browser, serta buku panduan fitur interaktif bawaan (`F1`).

### Mode Terang
<p align="center">
  <img src="assets/preview-light.png" alt="Arus! Download Manager - Mode Terang" width="100%" />
</p>

### Mode Gelap
<p align="center">
  <img src="assets/preview-dark.png" alt="Arus! Download Manager - Mode Gelap" width="100%" />
</p>

---

## Kemampuan Utama

### 1. Mesin Unduhan, Dekripsi Cloud, & Reliabilitas Jaringan

| Kemampuan | Penjelasan |
|---|---|
| **Akselerasi Multi-Segmen Dinamis** | Memecah unduhan HTTP/HTTPS hingga 16 koneksi paralel dengan algoritma *dynamic work-stealing* (segmen yang selesai lebih awal otomatis membantu membelah sisa segmen terberat) serta grafik laju transfer *real-time*. |
| **Dekripsi Native MEGA.nz & Smart Cloud** | Mendukung dekripsi `AES-128-CTR` multi-segmen bawaan untuk berkas dan folder publik **MEGA.nz**, serta ekstraksi tautan langsung otomatis untuk **Google Drive** (termasuk berkas >100 MB), **MediaFire**, **OneDrive (`1drv.ms`)**, **WeTransfer (`we.tl`)**, **Dropbox**, **Pixeldrain**, **GoFile**, **Buzzheavier**, **KrakenFiles**, **Workupload**, **Internet Archive**, **Hugging Face**, **GitHub Releases**, **SourceForge**, **Wikimedia**, dan **arXiv**. |
| **Pemulihan Koneksi & Anti-Sleep** | Mendeteksi koneksi macet (*stall recovery*), melanjutkan unduhan otomatis saat jaringan kembali tersambung dari gangguan Wi-Fi/ISP, dan mencegah Windows masuk ke mode *Sleep* selama ada unduhan aktif. |
| **Pembaruan Tautan Kedaluwarsa** | Melanjutkan unduhan berukuran besar yang terhenti akibat tautan sementara kedaluwarsa (`HTTP 403` / `410`) cukup dengan memperbarui alamat unduhan tanpa mengulang progres dari awal. |
| **Mode Hemat Bandwidth & Kuota Harian** | Sakelar satu klik pada bilah status dan *System Tray* untuk membatasi pemakaian bandwidth saat rapat daring atau bermain gim, dilengkapi pembatas **Kuota Data Harian (GB/hari)** otomatis. |
| **BitTorrent, Magnet, & Pilih Berkas** | Mendukung berkas `.torrent` dan tautan `magnet:?` lengkap dengan **pemilihan berkas spesifik di dalam torrent**, pengambilan metadata daftar berkas Magnet dari jaringan DHT/peer, pengaturan batas unggah/durasi *seeding*, serta dukungan Proxy Sistem, `HTTP`, dan `SOCKS5` dengan enkripsi kredensial Windows DPAPI. |

### 2. Pengunduh Video, Audio, Galeri 65+ Platform, & Konversi Media

| Kemampuan | Penjelasan |
|---|---|
| **65+ Platform Sosial, Video, & Kreator** | Mengunduh video hingga 4K, *playlist*, audio, serta galeri foto/*carousel* resolusi asli dari **YouTube**, **TikTok** (video & *slideshow* `/photo/`), **Instagram** (Reels, Carousel campuran video+foto, Stories), **X/Twitter**, **Facebook**, **Threads**, **Pinterest**, **Telegram**, **Reddit**, **LinkedIn**, **Bluesky**, **Snapchat**, **Tumblr**, **Bilibili/Bstation**, **Vimeo**, **Twitch**, **Kick**, **Pixiv**, **DeviantArt**, **ArtStation**, **Behance**, **Dribbble**, **SoundCloud**, **Bandcamp**, **Suno**, **Udio**, **Civitai**, dan puluhan lainnya. |
| **Pengunduh Stream HLS/DASH Otomatis** | Mengenali tautan *streaming* video tersegmen (`.m3u8` dan `.mpd`) lalu menggabungkan seluruh segmen secara otomatis menjadi satu berkas video `.mp4` utuh siap putar. |
| **Pemotong Klip & YouTube Chapter** | Mengunduh rentang durasi tertentu (`mm:ss` hingga `mm:ss`) atau memilih bab (*chapter*) video YouTube secara langsung sehingga tidak perlu mengunduh keseluruhan berkas video. |
| **Ekstraksi MP3 320kbps & Thumbnail** | Mengekstrak audio langsung ke format `.mp3` 320kbps lengkap dengan sampul album (*cover art*) dan metadata ID3, serta opsi penyimpanan gambar *thumbnail* resolusi asli. |
| **Konverter Media Offline Bawaan** | Mengonversi berkas video atau audio yang sudah terunduh menjadi **MP3 320kbps**, **GIF animasi**, atau **MP4 ringkas (H.264)** langsung dari menu klik kanan tanpa koneksi internet. |

### 3. Manajemen Berkas, Antrean Tenang, & Otomasi

| Kemampuan | Penjelasan |
|---|---|
| **Page Link & Media Grabber (`Ctrl+G`)** | Memindai satu halaman web atau repositori untuk mengekstrak banyak berkas sekaligus (dokumen PDF/Office, arsip, media, maupun galeri gambar beresolusi penuh) lengkap dengan penyaring tipe berkas dan pembuatan subfolder otomatis. |
| **Antrean Massal Rapi Tanpa Spam Taskbar** | Unduhan multi-slide, *playlist*, *Grab Page*, dan *Batch Add* berjalan tenang di jendela utama tanpa menumpuk jendela progres per item di Taskbar, disertai satu notifikasi ringkas saat seluruh grup selesai. |
| **Relokasi Saat Penyimpanan Penuh** | Memeriksa sisa ruang penyimpanan sebelum dan selama proses unduh. Ketika partisi tujuan penuh, berkas sementara (`.aruspart`) dapat dipindahkan ke drive lain untuk dilanjutkan tanpa kehilangan progres. |
| **Ekstraksi Arsip Universal** | Mengekstrak arsip `.zip`, `.rar`, `.7z`, `.tar.gz`, `.tar.xz`, dan `.tgz` secara otomatis saat selesai maupun secara manual ke subfolder terpisah melalui menu klik kanan. |
| **Aturan Folder Pintar, Panduan (`F1`), & Ganti Nama (`F2`)** | Mengarahkan lokasi penyimpanan otomatis berdasarkan domain atau ekstensi berkas (*Smart Folder Rules*), membuka buku panduan fitur instan dengan `F1`, serta mengganti nama berkas menggunakan `F2`. |
| **Manajemen Antrean, Penjadwal, & Cadangan** | Mendukung *Force Start*, prioritas antrean, penjadwalan jam mulai/berhenti harian, pola angka (`[01-20]`), opsi *Sleep*/*Shutdown* otomatis setelah selesai, pemantau *clipboard* non-intrusif, widget melayang, dan ekspor/impor cadangan (`.json`). |

### 4. Integrasi Browser Lintas Mesin, Keamanan, & Pembaruan

| Kemampuan | Penjelasan |
|---|---|
| **Ekstensi Resmi Chrome & Firefox (Manifest V3)** | Tersedia resmi di **[Chrome Web Store](https://chromewebstore.google.com/detail/mdidagnhjbilkgbafhchnghoflbakfmk)** (Chrome, Edge, Brave, Opera, Vivaldi) dan **[Mozilla Add-ons](https://addons.mozilla.org/firefox/addon/arus-download-manager/)** (Firefox, Zen Browser, Floorp, Waterfox, LibreWolf) — dilengkapi intersepsi unduhan otomatis, tombol melayang pintar untuk video & *carousel* campuran (video + gambar), serta klik kanan penembus *overlay* gambar resolusi asli. |
| **Pemindaian Windows Defender** | Memindai berkas yang selesai diunduh secara otomatis menggunakan mesin **Windows Defender** lokal (termasuk pemeriksaan isi arsip) dan menerapkan penanda keamanan standar Windows (*Mark-of-the-Web*). |
| **Verifikasi Hash & Pembaruan Aman** | Dilengkapi fitur pencocokan *checksum* `SHA-256` dan `MD5` langsung pada panel inspeksi berkas, serta *Auto-Updater* aplikasi bawaan yang mewajibkan verifikasi integritas `SHA-256` sebelum instalasi. |

---

## Instalasi

1. Buka halaman **[Releases Terbaru](https://github.com/baharida/arus-download-manager/releases/latest)**.
2. Unduh berkas **`Arus-Setup-x.y.z.exe`** (*Full Offline Installer* untuk pemasangan awal maupun pembaruan manual).
   *Catatan: Berkas `Arus-Update-x.y.z.exe` digunakan secara otomatis oleh fitur Auto-Updater di dalam aplikasi.*
3. Jalankan installer dan ikuti langkah pemasangan hingga selesai. Seluruh dependensi runtime dan mesin pengolah media sudah termasuk di dalam paket instalasi.
4. Pasang ekstensi pendamping sesuai browser pilihan Anda:
   - **Google Chrome, Microsoft Edge, Brave, Opera, Vivaldi:** Pasang melalui **[Chrome Web Store](https://chromewebstore.google.com/detail/mdidagnhjbilkgbafhchnghoflbakfmk)**.
   - **Mozilla Firefox, Zen Browser, Floorp, Waterfox, LibreWolf:** Pasang melalui **[Mozilla Firefox Add-ons](https://addons.mozilla.org/firefox/addon/arus-download-manager/)**.

> **Informasi Windows SmartScreen:** Apabila muncul peringatan *"Windows protected your PC"* saat menjalankan installer, klik **More info** lalu pilih **Run anyway**. Hal ini wajar untuk perangkat lunak independen yang didistribusikan secara gratis tanpa sertifikat *Extended Validation (EV)* berbayar. Setiap rilis selalu menyertakan berkas **`checksums.txt`** (`SHA-256`) untuk verifikasi keaslian paket instalasi.

---

## Arsitektur & Privasi

- **Komunikasi Lokal Terisolasi:** Integrasi antara ekstensi browser (`chrome-extension://` maupun `moz-extension://`) dan aplikasi desktop hanya berjalan melalui soket *loopback* lokal (`127.0.0.1`) yang memvalidasi identitas ekstensi dan menolak seluruh permintaan dari situs web eksternal (*anti-CSRF & anti-DNS rebinding*).
- **Tanpa Pengumpulan Data:** Aplikasi dan ekstensi bekerja sepenuhnya di perangkat lokal pengguna tanpa telemetri, pelacakan riwayat unduhan, iklan, maupun pengiriman data ke server perantara.
- **Penyimpanan Kredensial Terlindungi:** Kredensial sensitif seperti kata sandi proxy dienkripsi di penyimpanan lokal menggunakan mekanisme *Windows Data Protection API (DPAPI)* khusus akun pengguna aktif.
