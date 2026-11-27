# 📹 Kalsel CCTV Streams (Unofficial)

<!-- LINKS:START -->
[![Update](https://github.com/akuncadangans1tu-beep/Kalsel-CCTV-Streams/actions/workflows/update-streams.yml/badge.svg)](https://github.com/akuncadangans1tu-beep/Kalsel-CCTV-Streams/actions/workflows/update-streams.yml)
[![Kamera](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fakuncadangans1tu-beep%2FKalsel-CCTV-Streams%2Fmain%2Fstatus.json&query=%24.summary.total&label=kamera&color=blue)](https://github.com/akuncadangans1tu-beep/Kalsel-CCTV-Streams/blob/main/status.json)
[![Live](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fakuncadangans1tu-beep%2FKalsel-CCTV-Streams%2Fmain%2Fstatus.json&query=%24.summary.live&label=live&color=brightgreen)](https://github.com/akuncadangans1tu-beep/Kalsel-CCTV-Streams/blob/main/status.json)

```text
https://raw.githubusercontent.com/akuncadangans1tu-beep/Kalsel-CCTV-Streams/main/streams.m3u8
```

![QR](https://api.qrserver.com/v1/create-qr-code/?size=220x220&data=https%3A%2F%2Fraw.githubusercontent.com%2Fakuncadangans1tu-beep%2FKalsel-CCTV-Streams%2Fmain%2Fstreams.m3u8)
<!-- LINKS:END -->

Playlist CCTV publik **Kalimantan Selatan** — Kota Banjarbaru & Kota Banjarmasin (HLS `.m3u8` stabil), **dirawat otomatis tiap hari**. Ala IPTV-Org, fokus Kalsel.

## 🚧 Status Proyek
Dirawat otomatis tiap hari. Sebagian kamera bisa offline sesaat (wajar, biasanya pulih sendiri); cakupan terus bertambah.

## ⚠️ Disclaimer Penting (Sanggahan)
Pengembangan independen, **tidak berhubungan resmi** dengan instansi pemerintah mana pun.
* **Bukan produk Pemkot Banjarbaru / Banjarmasin / DisHub** — tidak bekerja sama, tidak didukung, tidak memakai server internal mereka.
* **Sumber Data** — seluruh tautan dari sumber publik yang terbuka di internet.

## 📡 Sumber
| Sumber | Cakupan |
|---|---|
| `cctv.banjarbarukota.go.id` (pemkot) | Kamera kota Banjarbaru |
| `cctv.banjarmasinkota.go.id` (pemkot) | Kamera kota Banjarmasin |

Hanya HLS langsung yang **stabil** (tanpa token/sementara). Sumber bertoken (mis. Kab Banjar) atau di balik Cloudflare (mis. Tabalong) sengaja tidak dipakai.

## 🚀 Fitur
* Satu playlist utama: `streams.m3u8` (HLS).
* **Thumbnail otomatis** (`tvg-logo`) per kamera, refresh mingguan.
* Grouping per **kategori / kota**.
* **Dataset uptime harian** (`data/uptime.csv`) + **CHANGELOG** + laporan kualitas (resolusi/bitrate).
* Cek & hapus link mati otomatis (grace 3 hari); kamera yang dihapus otomatis dibuatkan **Issue**.

## 🛠️ Cara Penggunaan
Salin tautan playlist pada blok di atas ke VLC / PotPlayer / app IPTV, atau scan QR-nya.

## 📊 Status Kamera
<!-- STATUS:START -->
> 🕒 **27 Nov 2026 09:41 WIB** · Total **64** · 🟢 **52** · 🔴 **12**

| Kamera | Grup | Status | Uptime | Kualitas |
|---|---|:--:|:--:|:--:|
| A1 SPBU Simpang 4 | Banjarbaru | 🟢 | 75% | 1280x720 |
| A2 Ulin Simpang 4 | Banjarbaru | 🟢 | 100% | 1280x720 |
| A3 PTZ Simpang 4 | Banjarbaru | 🟢 | 75% | 1920x1080 |
| Arah Dispenduk Pangeran Antasari | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Arah Gerbang ULM | Banjarbaru | 🔴 | 50% | 1280x720 |
| Arah Museum | Banjarbaru | 🟢 | 75% | 1280x720 |
| Arah Polresta | Banjarbaru | 🟢 | 100% | 1280x720 |
| Arah Purnama ULM | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Brimob Arah Simpang 3 | Banjarbaru | 🟢 | 100% | 2688x1520 |
| Bundaran Palam Trikora Taman PAMA | Banjarbaru | 🟢 | 75% | 2560x1440 |
| Bundaran Topi Toga | Banjarbaru | 🟢 | 75% | 1920x1080 |
| Bundaran Trikora Masjid Al-munawarah | Banjarbaru | 🟢 | 75% | 2560x1440 |
| C2 Banjarmasin Simpang 4 | Banjarbaru | 🔴 | 75% | 1920x1080 |
| C3 PTZ Simpang 4 | Banjarbaru | 🔴 | 75% | 1920x1080 |
| CCTV Pertigaan Trikora Arah RO Ulin | Banjarbaru | 🔴 | 75% | 2560x1440 |
| Depan G.bhayangkara | Banjarbaru | 🟢 | 75% | 2560x1440 |
| Depan STIMIK Arah Banjarmasin | Banjarbaru | 🔴 | 50% | 2560x1440 |
| Halte_minggu_raya | Banjarbaru | 🔴 | 50% | 1920x1080 |
| Jembatan Al-mansyur | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Jembatan Cempaka 1 | Banjarbaru | 🟢 | 100% | 640x480 |
| Jembatan Cempaka 2 | Banjarbaru | 🔴 | 67% | 2560x1440 |
| Jembatan Kembar Arah Banjarbaru | Banjarbaru | 🟢 | 100% | 2688x1520 |
| Jembatan Kembar Arah Banjarmasin | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Jembatan Kemuning | Banjarbaru | 🔴 | 75% | 1920x1080 |
| JPO Dalam Utara | Banjarbaru | 🟢 | 75% | 2688x1520 |
| JPO Tangga Selatan | Banjarbaru | 🟢 | 100% | 2688x1520 |
| JPO Tangga Utara | Banjarbaru | 🟢 | 100% | 2688x1520 |
| KM33 Utara Arah Banjarbaru | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Lapangan Murdjani PTZ | Banjarbaru | 🟢 | 100% | 1920x1080 |
| Pertigaan Ambulung | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Pertigaan Trikora RO Ulin Arah Masjid Agung | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Polsek BJB Arah Banjarmasin | Banjarbaru | 🟢 | 100% | 2560x1440 |
| PTZ Brimob Arah Palam | Banjarbaru | 🟢 | 100% | 1920x1080 |
| PTZ RO Ulin 33 Arah Banjarmasin | Banjarbaru | 🔴 | 67% | 1920x1080 |
| PTZ Taman Mawar Arah SD | Banjarbaru | 🔴 | 50% | 1920x1080 |
| QMALL Arah Batas Kota | Banjarbaru | 🟢 | 100% | 3072x1728 |
| QMALL Arah Simpang Empat | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Rebatig PTZ | Banjarbaru | 🟢 | 100% | 1920x1080 |
| STIMIK Arah Banjarbaru | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Sultan Agung Arah Banjarbaru | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Taman Minggu Raya | Banjarbaru | 🟢 | 100% | 2560x1440 |
| The Breeze Water Park | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Trikora Cempaka | Banjarbaru | 🔴 | 75% | 2560x1440 |
| Trikora Cempaka Arah Banjarbaru | Banjarbaru | 🟢 | 100% | 2560x1440 |
| Bundaran Pintu Masuk Sabilal | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Halaman Jembatan Pulau Bromo | Banjarmasin | 🔴 | 50% | — |
| Jembatan Patih Sisi Kanan | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Jembatan Patih Turunan kanan | Banjarmasin | 🟢 | 100% | 1280x720 |
| Jembatan Pulau Bromo Turunan | Banjarmasin | 🟢 | 100% | 1280x720 |
| Jembatan SakaHarang | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Pulau Insan | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Samping Tugu 0km | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Siring 0km | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Siring 0km 2 | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Siring 0km Panggung | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Siring Pos Dermaga | Banjarmasin | 🟢 | 100% | 1280x720 |
| Taman Jahri Saleh Pintu Masuk | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Taman Jahri Saleh View 1 | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Taman Jahri Saleh View 2 | Banjarmasin | 🟢 | 100% | 1920x1080 |
| Taman Kelayan Basket | Banjarmasin | 🟢 | 100% | 2560x1440 |
| Taman Kelayan Sungai | Banjarmasin | 🟢 | 100% | 1920x1080 |
| TPS Kuripan | Banjarmasin | 🟢 | 100% | 1280x720 |
| TPS Kuripan kanan | Banjarmasin | 🟢 | 100% | 1920x1080 |
| TPS Kuripan kiri | Banjarmasin | 🟢 | 100% | 1280x720 |

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
⚠️ **Harus kamera publik di Kalimantan Selatan! Kamera pribadi (kantor, rumah, dll.) dilarang kecuali memang untuk publik.**
