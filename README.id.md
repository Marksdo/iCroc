# README.md
- [English](README.md)
- [Deutsch](README.de.md)
- [Spanish](README.es.md)
- [Finnish](README.fi.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [Indonesian](README.id.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)
- [Norwegian](README.nb.md)
- [Dutch](README.nl.md)
- [Polish](README.pl.md)
- [Portuguese](README.pt.md)
- [Swedish](README.sv.md)
- [ภาษาไทย](README.th.md)
- [Turkish](README.tr.md)
- [Ukrainian](README.uk.md)
- [Vietnamese](README.vi.md)

# iCroc - Aplikasi CLI Croc untuk iOS & macOS

Unduh [rilis terbaru dari appstore](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Desain ulang total antarmuka aplikasi dan logika operasi.
- Tingkatkan versi croc tersemat ke v10.0.8
- Tambahkan dukungan fitur handoff iOS & macOS
- Dukung lebih banyak bahasa

V1.1
---
- Desain ulang ikon aplikasi
- Perbaikan bug dan peningkatan kinerja.

V1.0
---
croc adalah alat yang memungkinkan dua komputer untuk mentransfer file dan folder dengan mudah dan aman. Sejauh yang saya tahu, croc adalah satu-satunya alat transfer file CLI yang melakukan semua hal berikut:

- memungkinkan dua komputer untuk mentransfer data (menggunakan relay)
- menyediakan enkripsi ujung-ke-ujung (menggunakan PAKE)
- memungkinkan transfer lintas platform yang mudah (Windows, Linux, Mac)
- memungkinkan transfer beberapa file
- memungkinkan melanjutkan transfer yang terputus
- server lokal atau penerusan port tidak diperlukan
- ipv6-pertama dengan fallback ipv4
- dapat menggunakan proxy, seperti tor

Aplikasi baris perintah yang menjadi dasar ini dapat ditemukan di sini:

https://github.com/schollz/croc

## Aktifkan iCroc di macOS dalam Pengaturan
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Kirim file dengan cepat menggunakan iCroc
- Pilih file di Finder lalu gunakan buka dengan iCroc
- Di Finder, pilih file dan ⌘+C untuk menyalin lalu buka iCroc dan gunakan ⌘+V untuk mengirim file
- Seret file ke iCroc

# ⚡ Handoff
- Perangkat iOS & macOS harus sama-sama menginstal aplikasi iCroc
- iOS & macOS mengaktifkan fitur Handoff
- Ketika pengirim menghasilkan kode-frasa, perangkat lain yang menggunakan iCroc akan secara otomatis mendapatkan kode-frasa

# 🔮 Lanjutkan tugas yang terputus
- Pengirim mengirim ulang file dan penerima menggunakan format kode-frasa baru@kode-frasa lama contohnya: 4161-mambo-young-baby@7611-south-concept-satire
- Pengirim mengirim ulang file menggunakan token khusus sebagai kode-frasa sebelumnya

# 💾 Folder penerima khusus
- Folder penerima akan disimpan di ~/Downloads/'${kode-frasa}'
- Gunakan '@namaFolder' untuk menyimpan di ~/Downloads/namaFolder contohnya: 8443-siren-mayor-origin@mypics
- Gunakan folder target yang sama akan secara otomatis melanjutkan tugas transfer yang terputus