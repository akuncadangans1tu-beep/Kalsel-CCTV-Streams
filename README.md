# 📹 Banjarbaru CCTV Streams (Unofficial)

<!-- LINKS:START -->
_Badge, tautan playlist, dan QR dibuat otomatis pada run pertama._
<!-- LINKS:END -->

Playlist CCTV publik **Kota Banjarbaru, Kalimantan Selatan** (HLS `.m3u8` stabil), **dirawat otomatis tiap hari**. Ala IPTV-Org, tapi fokus Banjarbaru.

## 🚧 Status Proyek
Dirawat otomatis tiap hari. Sebagian kamera bisa offline sesaat (wajar, biasanya pulih sendiri); cakupan terus bertambah.

## ⚠️ Disclaimer Penting (Sanggahan)
Pengembangan independen, **tidak berhubungan resmi** dengan instansi pemerintah mana pun.
* **Bukan produk Pemkot Banjarbaru / DisHub** — tidak bekerja sama, tidak didukung, tidak memakai server internal mereka.
* **Sumber Data** — seluruh tautan dari sumber publik yang terbuka di internet (`cctv.banjarbarukota.go.id`).

## 📡 Sumber
| Sumber | Cakupan |
|---|---|
| `cctv.banjarbarukota.go.id` (pemkot) | Kamera kota Banjarbaru (±69 titik) |

Hanya HLS langsung yang **stabil** (tanpa token/sementara).

## 🚀 Fitur
* Satu playlist utama: `streams.m3u8` (HLS).
* **Thumbnail otomatis** (`tvg-logo`) per kamera, refresh mingguan.
* Grouping per **kategori** kamera (lalu lintas, taman, JPO, dll.).
* **Dataset uptime harian** (`data/uptime.csv`) + **CHANGELOG** + laporan kualitas (resolusi/bitrate).
* Cek & hapus link mati otomatis (grace 3 hari); kamera yang dihapus otomatis dibuatkan **Issue**.

## 🛠️ Cara Penggunaan
Salin tautan playlist pada blok di atas ke VLC / PotPlayer / app IPTV, atau scan QR-nya.

## 📊 Status Kamera
<!-- STATUS:START -->
_Tabel dibuat otomatis pada run pertama._
<!-- STATUS:END -->

## 📦 Data & Laporan
* [`data/uptime.csv`](data/uptime.csv) — dataset time-series online/offline + kualitas (open data).
* [`CHANGELOG.md`](CHANGELOG.md) — riwayat kamera masuk/keluar.
* [`REPORT.md`](REPORT.md) — laporan run terakhir.
* [`status.json`](status.json) — API mini (JSON) untuk developer.

## 🤖 Cara Kerja Otomatis
Tiap 03:00 WIB GitHub Actions: scrape sumber → kenali/migrasi entri lama → cek HLS (master→media→segmen) → hapus duplikat & yang mati 3 hari beruntun → tulis playlist, dataset, changelog, tabel README. Mingguan: refresh thumbnail via ffmpeg.

## 🤝 Kontribusi
Baca [CONTRIBUTING.md](CONTRIBUTING.md). Pakai template Issue untuk usul kamera baru / lapor kamera mati.
⚠️ **Harus kamera publik di Banjarbaru / Kalimantan Selatan! Kamera pribadi (kantor, rumah, dll.) dilarang kecuali memang untuk publik.**
