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
  <strong>Arus! Download Manager</strong> adalah aplikasi manajer unduhan native untuk Windows (64-bit) yang menggabungkan akselerasi HTTP/HTTPS multi-segmen, dekripsi cloud native, pengunduh video/audio &amp; galeri 65+ platform, konverter media offline, transfer QR Wi-Fi lokal ke ponsel, klien BitTorrent/Magnet, serta integrasi ekstensi browser resmi untuk ekosistem <strong>Chromium</strong> maupun <strong>Firefox</strong> dalam satu paket instalasi mandiri.
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

### 1. Mesin Unduhan, Multi-Mirror, & Dekripsi Cloud

| Kemampuan | Penjelasan |
|---|---|
| **Akselerasi Multi-Segmen Dinamis** | Memecah unduhan HTTP/HTTPS hingga 16 koneksi paralel dengan algoritma *dynamic work-stealing* (segmen yang selesai lebih awal otomatis membantu membelah sisa segmen terberat) serta grafik laju transfer *real-time*. |
| **Multi-Mirror Booster** | Menarik satu berkas besar dari beberapa tautan server cadangan (*mirror*) secara paralel dengan verifikasi ukuran `Content-Range` dan pengalihan (*failover*) otomatis apabila salah satu server melambat atau gagal. |
| **Dekripsi Native MEGA.nz & Smart Cloud** | Mendukung dekripsi `AES-128-CTR` multi-segmen bawaan untuk berkas dan folder publik **MEGA.nz**, serta ekstraksi tautan langsung otomatis untuk **Google Drive** (termasuk berkas >100 MB), **MediaFire**, **OneDrive (`1drv.ms`)**, **WeTransfer (`we.tl`)**, **Dropbox**, **Pixeldrain**, **GoFile**, **Buzzheavier**, **KrakenFiles**, **Workupload**, **Internet Archive**, **Hugging Face**, **GitHub Releases**, **SourceForge**, **Wikimedia**, dan **arXiv**. |
| **Pemulihan Koneksi & Tautan Kedaluwarsa** | Mendeteksi koneksi macet (*stall recovery*), melanjutkan otomatis saat jaringan tersambung kembali, mencegah Windows *Sleep* saat mengunduh, serta memperbarui alamat tautan kedaluwarsa (`HTTP 403` / `410`) tanpa mengulang dari 0%. |
| **Mode Hemat Bandwidth (`🐢 Saver`)** | Sakelar satu klik langsung di dalam **jendela progres unduhan**, bilah status utama, maupun *System Tray* untuk menahan pemakaian bandwidth seketika saat rapat daring atau bermain gim, dilengkapi pembatas **Kuota Data Harian (GB/hari)**. |
| **BitTorrent, Magnet, & Pilih Berkas** | Mendukung berkas `.torrent` dan tautan `magnet:?` lengkap dengan **pemilihan berkas spesifik di dalam torrent**, pengambilan metadata daftar berkas dari jaringan DHT/peer, pengaturan batas unggah/*seeding*, serta dukungan Proxy (`HTTP` / `SOCKS5` dengan enkripsi DPAPI). |

### 2. Video, Audio, Galeri 65+ Platform, & Alat Kreator

| Kemampuan | Penjelasan |
|---|---|
| **65+ Platform Sosial, Video, & Kreator** | Mengunduh video hingga 4K, *playlist*, audio, serta galeri foto/*carousel* resolusi asli dari **YouTube**, **TikTok** (video & *slideshow* `/photo/`), **Instagram** (Reels, Carousel campuran video+foto, Stories), **X/Twitter**, **Facebook**, **Threads**, **Pinterest**, **Telegram**, **Reddit**, **LinkedIn**, **Bluesky**, **Snapchat**, **Tumblr**, **Bilibili/Bstation**, **Vimeo**, **Twitch**, **Kick**, **Pixiv**, **DeviantArt**, **ArtStation**, **Behance**, **Dribbble**, **SoundCloud**, **Bandcamp**, **Suno**, **Udio**, **Civitai**, dan puluhan lainnya. |
| **Konversi Siap Edit & Tanam Subtitle** | Mengonversi video secara *on-demand* ke **MP4 H.264 Siap Edit** (mulus di Premiere Pro, DaVinci Resolve, & CapCut), **MP4 Hemat WhatsApp**, **MP3 320kbps** (+ *cover art*), **GIF animasi**, serta **menyematkan subtitle (`.srt` / `.vtt`)** ke dalam video secara *lossless* dalam hitungan detik. |
| **Gabung Gambar Carousel ke 1 PDF (*On-Demand*)** | Menyatukan *slide* gambar komik atau materi edukasi yang selesai diunduh menjadi satu dokumen `.pdf` sesuai rasio asli tiap halaman secara manual (tanpa mengubah atau menghapus berkas gambar asli). |
| **Stream HLS/DASH, Pemotong Klip, & Chapter** | Menggabungkan tautan *streaming* `.m3u8` / `.mpd` otomatis menjadi `.mp4` utuh, serta mengunduh potongan durasi tertentu (`mm:ss`–`mm:ss`) atau bab (*YouTube Chapters*) pilihan. |

### 3. Transfer ke Ponsel, Manajemen Berkas, & Otomasi

| Kemampuan | Penjelasan |
|---|---|
| **Kirim ke HP via QR Wi-Fi Lokal** | Mentransfer berkas yang selesai diunduh langsung ke ponsel Android/iOS melalui jaringan Wi-Fi lokal menggunakan kode QR bawaan—**tanpa memakan kuota internet dan 100% kualitas asli tanpa kompresi**. |
| **Salin Berkas Instan (`Ctrl+C`)** | Menyalin berkas fisik langsung ke *Clipboard* Windows dari dialog selesai maupun daftar utama sehingga dapat langsung ditempel (`Ctrl+V`) ke WhatsApp Desktop, Telegram, Discord, Word, atau Figma tanpa membuka File Explorer. |
| **Jendela Progres Grup Terpadu** | Unduhan multi-slide *carousel* dan antrean grup dipantau melalui satu jendela progres gabungan yang rapi lengkap dengan grafik kecepatan dan indikator *Taskbar* tanpa membanjiri layar dengan *pop-up*. |
| **Page Link & Media Grabber (`Ctrl+G`)** | Memindai satu halaman web, folder publik **MEGA.nz**, **GitHub Releases**, **Hugging Face**, atau **Archive.org** untuk memilih dan mengunduh banyak berkas sekaligus. |
| **Ekstraksi Arsip, Relokasi Disk, & Perapi Riwayat** | Mengekstrak `.zip`, `.rar`, `.7z`, dan `.tar.gz` satu klik, memindahkan berkas sementara (`.aruspart`) lintas partisi saat penyimpanan penuh, serta membersihkan entri riwayat yang berkasnya telah dipindah dari disk dalam satu klik. |
| **Aturan Folder Pintar, Penjadwal, & Cadangan** | Mengarahkan folder simpan otomatis per domain/ekstensi, menjadwalkan jam antrean harian, opsi *Sleep*/*Shutdown* PC otomatis saat selesai, panduan cepat `F1`, serta ekspor/impor cadangan (`.json`). |

### 4. Integrasi Browser Lintas Mesin, Keamanan, & Pembaruan

| Kemampuan | Penjelasan |
|---|---|
| **Ekstensi Resmi Chrome & Firefox (Manifest V3)** | Tersedia resmi di **[Chrome Web Store](https://chromewebstore.google.com/detail/mdidagnhjbilkgbafhchnghoflbakfmk)** (Chrome, Edge, Brave, Opera, Vivaldi) dan **[Mozilla Add-ons](https://addons.mozilla.org/firefox/addon/arus-download-manager/)** (Firefox, Zen Browser, Floorp, Waterfox, LibreWolf) — dilengkapi intersepsi unduhan pintar, tombol melayang untuk video & *carousel*, serta klik kanan penembus *overlay* gambar resolusi asli. |
| **Pemindaian Windows Defender** | Memindai berkas yang selesai diunduh secara otomatis menggunakan mesin **Windows Defender** lokal (termasuk pemeriksaan isi arsip) dan menerapkan penanda keamanan standar Windows (*Mark-of-the-Web*). |
| **Verifikasi Hash & Pembaruan Aman** | Dilengkapi fitur pencocokan *checksum* `SHA-256` dan `MD5` langsung pada aplikasi, serta *Auto-Updater* bawaan yang mewajibkan verifikasi integritas `SHA-256` sebelum instalasi. |

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

---

## Dukung Pengembangan

**Arus! Download Manager** dikembangkan secara independen dan dibagikan sepenuhnya **gratis tanpa iklan, tanpa batasan fitur, dan tanpa pelacakan**. Jika aplikasi ini membantu mempercepat pekerjaan harian Anda, dukungan sukarela Anda sangat berarti untuk menjaga pengembangan dan pemeliharaan rilis berikutnya tetap berjalan:

<p align="center">
  <a href="https://saweria.co/baharida">
    <img src="https://img.shields.io/badge/Saweria-QRIS%20%2F%20Dukungan%20Lokal-D97706?style=for-the-badge" height="36" alt="Dukung via Saweria (QRIS)" />
  </a>
  &nbsp;
  <a href="https://ko-fi.com/baharida">
    <img src="https://img.shields.io/badge/Ko--fi-Support%20on%20Ko--fi-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white" height="36" alt="Support on Ko-fi" />
  </a>
</p>
