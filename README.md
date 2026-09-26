# IITrack

IITrack membantu tim Inkubator IT (IIT), HMIF ITB, mengelola proyek di satu tempat. Di sini tim bisa melihat proyek, penanggung jawab, progress, dan dokumen yang berkaitan.

## Tampilan aplikasi

Ada empat area utama: **Dashboard**, **Project**, **Settings**, dan **Notifications**. Di dalam Project, All Projects punya dua pilihan: **Active Projects** dan **Past Projects**. Ini satu area fitur, bukan banyak menu terpisah.

## Cara membaca issue

Judul issue dibuat singkat. Penjelasan pekerjaan, batas scope, kriteria selesai, serta tautan bukti ada di deskripsinya. Angka seperti `#129` adalah nomor issue GitHub. Kode dalam kurung siku memudahkan tim menghubungkan fitur induk dengan tugasnya; kode tersebut adalah penamaan internal IITrack, bukan aturan baku GitHub.

| Kode | Artinya di proyek ini | Contoh |
| --- | --- | --- |
| `F03` | Fitur nomor 03. `F03` membahas hak akses berdasarkan peran. Angka lain menunjuk fitur lain di backlog. | `[F03]` |
| `T01`, `T02` | Tugas bernomor di bawah fitur atau kelompok pekerjaan. | `[F03-T01]` adalah tugas pertama untuk F03. |
| `INF` | Fondasi teknis, seperti struktur repositori, basis data awal, dan pemeriksaan otomatis. | `[INF-T02]` adalah tugas kedua untuk fondasi teknis. |
| `XC` | Pekerjaan lintas fitur, misalnya integrasi, pengujian, perbaikan temuan, dan serah terima. Nomor setelahnya membedakan kelompok. | `[XC-08]` mencatat UAT. |
| `RW-S2` | Perbaikan ulang antarmuka yang direncanakan pada Sprint 2. `RW` berarti *rework*, sedangkan `S2` berarti Sprint 2. | `[RW-S2-T01]` adalah tugas navigasi untuk perbaikan tersebut. |
| `PM` | Pekerjaan manajemen proyek. | `[PM]` UAT. |

Contohnya, `[F03-T01]` bukan fitur baru yang terlihat di menu. Itu tugas teknis untuk fitur F03. Demikian juga #130 sampai #135 adalah tugas di bawah **satu** fitur antarmuka #129.

## Progress dan sprint

[Papan Sprint 1 dan 2](https://github.com/orgs/Operational-IIT-Workspace/projects/17/views/8) memisahkan pekerjaan berdasarkan sprint yang direncanakan. [Tampilan empat area](https://github.com/orgs/Operational-IIT-Workspace/projects/17/views/9) memperlihatkan ringkasan antarmuka.

Sprint 1 memuat pekerjaan yang sudah selesai, termasuk penetapan hasil kerja dan revisi PRD di #136. UAT sedang berjalan pada Sprint 2 di #37. BAST ada di #35, dan User Guide ada di #110. Status pada papan menunjukkan progress pekerjaan; penempatan pada sprint saja belum berarti pekerjaan selesai.

Item di luar scope tidak masuk Sprint 2. Kalau ada judul yang terasa samar, buka deskripsi issue dan lihat bagian Objective, pekerjaan, serta bukti selesainya.
