# 📹 Banjarbaru CCTV Streams (Unofficial)

<!-- LINKS:START -->
[![Update](https://github.com/akuncadangans1tu-beep/BanjarBaru-CCTV-Streams/actions/workflows/update-streams.yml/badge.svg)](https://github.com/akuncadangans1tu-beep/BanjarBaru-CCTV-Streams/actions/workflows/update-streams.yml)
[![Kamera](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fakuncadangans1tu-beep%2FBanjarBaru-CCTV-Streams%2Fmain%2Fstatus.json&query=%24.summary.total&label=kamera&color=blue)](https://github.com/akuncadangans1tu-beep/BanjarBaru-CCTV-Streams/blob/main/status.json)
[![Live](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fakuncadangans1tu-beep%2FBanjarBaru-CCTV-Streams%2Fmain%2Fstatus.json&query=%24.summary.live&label=live&color=brightgreen)](https://github.com/akuncadangans1tu-beep/BanjarBaru-CCTV-Streams/blob/main/status.json)

```text
https://raw.githubusercontent.com/akuncadangans1tu-beep/BanjarBaru-CCTV-Streams/main/streams.m3u8
```

![QR](https://api.qrserver.com/v1/create-qr-code/?size=220x220&data=https%3A%2F%2Fraw.githubusercontent.com%2Fakuncadangans1tu-beep%2FBanjarBaru-CCTV-Streams%2Fmain%2Fstreams.m3u8)
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
> 🕒 **26 Nov 2026 19:54 WIB** · Total **41** · 🟢 **33** · 🔴 **8**

| Kamera | Grup | Status | Uptime | Kualitas |
|---|---|:--:|:--:|:--:|
| A1 SPBU Simpang 4 | Banjarbaru | 🔴 | 50% | 1280x720 |
| A2 Ulin Simpang 4 | Banjarbaru | 🟢 | 100% | 1280x720 |
| A3 PTZ Simpang 4 | Banjarbaru | 🔴 | 50% | 1920x1080 |
| Arah Dispenduk Pangeran Antasari | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Arah Gerbang ULM | Banjarbaru | 🟢 | 100% | 1280x720 |
| Arah Museum | Banjarbaru | 🟢 | 100% | 1280x720 |
| Arah Polresta | Banjarbaru | 🟢 | 100% | 1280x720 |
| Arah Purnama ULM | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Brimob Arah Simpang 3 | Banjarbaru | 🟢 | 100% | 2688x1520 |
| Bundaran Palam Trikora Taman PAMA | Banjarbaru | 🔴 | 50% | 2560x1440 |
| Bundaran Topi Toga | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Bundaran Trikora Masjid Al-munawarah | Banjarbaru | 🔴 | 50% | 2560x1440 |
| C2 Banjarmasin Simpang 4 | Banjarbaru | 🟢 | 100% | 1920x1080 |
| C3 PTZ Simpang 4 | Banjarbaru | 🟢 | 100% | 1920x1080 |
| CCTV Pertigaan Trikora Arah RO Ulin | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Depan G.bhayangkara | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Depan STIMIK Arah Banjarmasin | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Halte_minggu_raya | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Jembatan Al-mansyur | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Jembatan Cempaka 2 | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Jembatan Kembar Arah Banjarbaru | Banjarbaru | 🟢 | 100% | 2688x1520 |
| Jembatan Kemuning | Banjarbaru | 🟢 | 100% | 1920x1080 |
| JPO Dalam Utara | Banjarbaru | 🔴 | 50% | 2688x1520 |
| KM33 Utara Arah Banjarbaru | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Lapangan Murdjani PTZ | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Pertigaan Ambulung | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Pertigaan Sungai Ulin Arah Mandiangin | Banjarbaru | 🔴 | 50% | 1920x1080 |
| Pertigaan Trikora RO Ulin Arah Masjid Agung | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Polsek BJB Arah Banjarmasin | Banjarbaru | 🟢 | 100% | 2560x1440 |
| PTZ Brimob Arah Palam | Banjarbaru | 🟢 | 100% | 1920x1080 |
| PTZ RO Ulin 33 Arah Banjarmasin | Banjarbaru | 🟢 | 100% | 1920x1080 |
| PTZ Taman Mawar Arah SD | Banjarbaru | 🔴 | 50% | 1920x1080 |
| QMALL Arah Batas Kota | Banjarbaru | 🟢 | 100% | 3072x1728 |
| QMALL Arah Simpang Empat | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Rebatig PTZ | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Sultan Agung Arah Banjarbaru | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Taman Minggu Raya | Banjarbaru | 🟢 | 100% | 2560x1440 |
| The Breeze Water Park | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Trikora A.yani Ujung | Banjarbaru | 🔴 | 50% | 640x480 |
| Trikora Cempaka | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Trikora Cempaka Arah Banjarbaru | Banjarbaru | 🟢 | 100% | 2560x1440 |

_🔴 = gagal cek terakhir; dipertahankan maks 3 hari beruntun sebelum dihapus._
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
