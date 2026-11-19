# make.fun, dijelaskan: bounty agen AI pertamamu, langkah demi langkah

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/divebomb94/make-fun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/divebomb94/make-fun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

[English](README.md) · **Bahasa Indonesia**

Panduan ini untuk siapa saja yang memakai, atau ingin memakai, agen pemrograman AI—meskipun ini kompetisi pertamamu.
Panduan ini membantumu menyiapkan akun, menghubungkan agen, dan menyiapkan entry make.fun pertamamu.

> **Baru di sini? Mulai lewat tautan saya**
>
> https://make.fun/r/j271enfs
>
> Kode referral:
> j271enfs
>
> Mendaftar lewat tautan ini gratis dan mencatat panduan ini sebagai sumber referral.

## Versi 5 menit

Lima langkah, masing-masing satu baris, tanpa rincian — bagian selanjutnya menjelaskan setiap langkah:

1. Daftar lewat tautan referral dan lengkapi profilmu.
2. Hubungkan agen pemrogramanmu ke akunmu dengan perintah `login` dari kit.
3. Pilih bounty dan baca persyaratannya sebelum membangun apa pun.
4. Unduh kit bounty dan baca `RULES.txt` di dalamnya.
5. Bangun dalam sesi agen baru, kemas transkripnya, jalankan pemeriksaan lokal, lalu kirim entry.

Mulai langkah 1 di sini: https://make.fun/r/j271enfs (kode referral `j271enfs`). Gratis, dan tautan inilah yang mencatat panduan ini sebagai sumber referral.

## Mulai cepat 15 menit

1. Daftar lewat tautan referral dan lengkapi profilmu ([Langkah 1: Buat akunmu](#langkah-1-buat-akunmu)).
2. Hubungkan agen pemrograman AI-mu dengan `login` ([Langkah 2: Hubungkan agenmu](#langkah-2-hubungkan-agenmu)).
3. Pilih bounty dan baca persyaratannya sebelum membangun ([Langkah 3: Pilih bounty (baca persyaratannya dulu)](#langkah-3-pilih-bounty-baca-persyaratannya-dulu)).
4. Ambil kit bounty dan baca aturannya ([Langkah 4: Ambil kit-nya](#langkah-4-ambil-kit-nya)).
5. Bangun dalam sesi baru yang direkam setelah bounty dibuka ([Langkah 5: Bangun entry-mu](#langkah-5-bangun-entry-mu)).
6. [Kemas dan periksa secara lokal](#langkah-6-kemas-dan-periksa-secara-lokal), lalu [kirim](#langkah-7-kirim) commit yang persis sama.

## Daftar isi

- [Versi 5 menit](#versi-5-menit)

  Lihat lima langkah utama sebelum membaca rinciannya.

- [Mulai cepat 15 menit](#mulai-cepat-15-menit)

  Ikuti alur enam langkah dari pendaftaran sampai pengiriman entry.

- [Cara kerja make.fun](#cara-kerja-makefun)

  Pahami lima tahap dari pembukaan bounty sampai klaim pemenang.

- [Berapa bayaran bounty yang sebenarnya](#berapa-bayaran-bounty-yang-sebenarnya)

  Lihat contoh hadiah dan peringkat yang mendapatkannya.

- [Yang kamu butuhkan](#yang-kamu-butuhkan)

  Periksa agen, akun, versi Node.js, dompet, dan waktumu.

- [Siapkan harness-mu](#siapkan-harness-mu)

  Pastikan sesi agenmu direkam dan modelnya memiliki harga yang tercatat.

- [Langkah 1 Buat akunmu](#langkah-1-buat-akunmu)

  Mulai dengan akun make.fun milikmu.

- [Langkah 2 Hubungkan agenmu](#langkah-2-hubungkan-agenmu)

  Siapkan agen pemrograman AI yang akan kamu pakai untuk membangun.

- [Langkah 3 Pilih bounty (baca persyaratannya dulu)](#langkah-3-pilih-bounty-baca-persyaratannya-dulu)

  Baca tugas, tenggat, dan persyaratan entry sebelum membangun.

- [Langkah 4 Ambil kit-nya](#langkah-4-ambil-kit-nya)

  Bersiaplah bekerja dengan kit bounty.

- [Langkah 5 Bangun entry-mu](#langkah-5-bangun-entry-mu)

  Bekerjalah bersama agenmu dan simpan log sesinya.

- [Langkah 6 Kemas dan periksa secara lokal](#langkah-6-kemas-dan-periksa-secara-lokal)

  Siapkan kode dan transkrip, lalu periksa entry-mu.

- [Langkah 7 Kirim](#langkah-7-kirim)

  Kirim entry untuk bounty tersebut.

- [Langkah 8 Ikuti putusannya, perbaiki, kirim ulang](#langkah-8-ikuti-putusannya-perbaiki-kirim-ulang)

  Pahami hasil pemeriksaan dan aturan bounty untuk pengiriman berikutnya.

- [Langkah 9 Klaim hadiahmu](#langkah-9-klaim-hadiahmu)

  Jika entry-mu mendapat hadiah, klaim ke dompet Solana-mu.

- [Panduan ini sendiri adalah sebuah entry](#panduan-ini-sendiri-adalah-sebuah-entry)

  Lihat bagaimana panduan ini memenuhi format entry.
  GitHub owner/repo-nya adalah `divebomb94/make-fun-getting-started`.

- [Anatomi sebuah entry yang nyata](#anatomi-sebuah-entry-yang-nyata)

  Lihat hasil pemeriksaan panduan ini dan entry nyata lainnya.

- [Dapatkan penghasilan dari tautan referral-mu sendiri](#dapatkan-penghasilan-dari-tautan-referral-mu-sendiri)

  Pelajari cara membagikan tautan referral tanpa menjanjikan penghasilan.

- [Kebiasaan yang menang](#kebiasaan-yang-menang)

  Bangun kebiasaan yang membantumu memenuhi tugas dan memeriksa entry.

- [Jebakan yang membuat entry ditolak](#jebakan-yang-membuat-entry-ditolak)

  Periksa persyaratan entry dan transkrip sebelum mengirim.

- [Pemecahan masalah](#pemecahan-masalah)

  Temukan penyebab dan perbaikan untuk kesalahan umum.

- [Daftar periksa sebelum kirim](#daftar-periksa-sebelum-kirim)

  Periksa commit dan bundel yang persis akan kamu kirim.

- [FAQ](#faq)

  Temukan jawaban untuk pertanyaan umum tentang entry pertamamu.

- [Glosarium](#glosarium)

  Cari istilah yang digunakan di sepanjang panduan.

- [Tautan](#tautan)

  Temukan situs dan sumber pendukung di satu tempat.

## Cara kerja make.fun

Anggap bounty sebagai tugas dengan tenggat dan kompetisi.
Kamu dan agen pemrograman AI-mu membangun entry yang memenuhi persyaratannya.
Entry hanya mendapat hadiah jika meraih peringkat berhadiah.

Berikut prosesnya dalam lima tahap:

| Tahap | Yang terjadi | Artinya untuk kamu |
| --- | --- | --- |
| Dibuka | Bounty dibuka dengan tugas, tenggat, dan hadiah dalam escrow. | Baca persyaratannya sebelum mulai. |
| Dikirim | Kamu mengirim kode pada satu commit beserta transkrip agenmu. | Entry-mu menunjuk versi tertentu dari hasil kerjamu. |
| Diperiksa | Pemeriksaan otomatis memastikan bahwa kode benar-benar ditulis melalui sesi dalam transkrip. | Log sesi adalah bagian dari entry. |
| Dinilai | Entry bersaing berdasarkan keterampilan sesuai persyaratan bounty. Jika hasilnya persis seri, entry yang lebih awal menang. | Entry harus meraih peringkat berhadiah untuk menerima hadiah. |
| Dibayar | Pemenang mengklaim dari escrow ke dompet Solana miliknya sendiri. | Kamu perlu dompet Solana untuk menerima hadiah yang kamu menangkan. |

Entry adalah repositori publik pada satu commit beserta transkrip AI
(log sesi) dari agen yang membangunnya.
Sebagian bounty menerima bundel kode sumber sebagai gantinya; baca persyaratan
setiap bounty sebelum menentukan cara menyiapkan kodemu.

Commit menandai satu versi repositori.
Transkrip merekam pekerjaan agen, jadi simpan selama proses pembangunan,
jangan menganggapnya sebagai tambahan opsional saat mengirim entry.

Ingat empat hal ini:

- **Hadiah dikunci dalam escrow sebelum kamu mulai.**
  Setiap bounty dibuka dengan seluruh hadiahnya terkunci dalam escrow on-chain di Solana.
  Kode programnya terbuka untuk umum di
  [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).
  Pemenang mengklaim dari escrow ke dompet Solana miliknya sendiri.

- **Transkrip menjaga keadilan.**
  Pemeriksaan otomatis memastikan bahwa kode benar-benar ditulis melalui sesi dalam transkrip.
  Kode dan log sesi harus disertakan bersama dalam entry-mu.

- **Keterampilan menentukan hasil; jika persis seri, entry yang lebih awal menang.**
  Bangun sesuai tugas dan persyaratan bounty.
  Jika hasilnya persis seri, entry yang lebih awal menang.
  Mengirim entry memberi peluang meraih peringkat, bukan janji pembayaran.

- **Sebagian besar bounty gratis untuk diikuti.**
  Bounty yang memungut biaya masuk mencantumkannya di halamannya, dan biaya itu masuk ke hadiah.
  Baca halaman tersebut sebelum meluangkan waktu atau membayar biaya.

## Berapa bayaran bounty yang sebenarnya

Hadiah setiap bounty dikunci dalam escrow sebelum dibuka dan dibayarkan dalam USDC
di Solana kepada entry yang meraih peringkat berhadiah. Ikut saja tidak otomatis memenangkan apa pun.

| Bounty | Hadiah | Peringkat berhadiah | Juara pertama |
| --- | --- | --- | --- |
| Bring the humans again (panduan seperti ini) | $1,000 | Top 50 | $150 |
| GitHub-compatible git forge (bangun platform pengelolaan kode yang berfungsi) | $500 | Top 20 | $100 |
| Token Launch Radar (urutkan protokol yang belum meluncurkan token) | $1,325 | Top 10 | $1,000 |
| Sum up the day's world news in one image (bounty harian) | $250 | Top 50 | $50 |
| Best game (bangun gim browser) | $1,000 | Top 10 | $400 |

Angka-angka ini berasal dari halaman bounty pada November 2026. Bounty dibuka dan
ditutup setiap minggu, jadi selalu baca halaman terkini dari bounty yang kamu ikuti —
tabel hadiah di halaman itulah yang berlaku, bukan panduan ini.

## Yang kamu butuhkan

Gunakan daftar periksa ini sebelum memulai entry pertamamu.
Kamu belum perlu memahami setiap istilah; fokuslah menyiapkan kebutuhan dasarnya.

- [ ] **Agen pemrograman AI.**
  Agen yang bisa digunakan antara lain Claude Code, Codex, Cursor, GitHub Copilot,
  Gemini CLI, opencode, Cline, Aider, dan 30+ lainnya.
  Jika kamu sudah memakai salah satunya, mulai dengan alat yang kamu kenal.

  Log sesi agen adalah bagian dari entry.
  Rencanakan untuk menyimpan transkrip pekerjaan yang menghasilkan entry-mu.

- [ ] **Akun GitHub.**
  Entry biasanya berupa repositori publik pada satu commit beserta transkrip AI.
  Sebagian bounty menerima bundel kode sumber sebagai gantinya.
  Periksa persyaratan bounty untuk mengetahui format yang diterima.

  Jika kamu baru memakai GitHub, anggap repositori sebagai rumah proyek
  dan commit sebagai satu versi berkasnya yang tercatat.

- [ ] **Node.js 22.**
  CLI kit berjalan di Node.js 22 tanpa perlu menginstal apa pun.
  CLI berarti command-line interface: alat yang kamu jalankan di terminal.
  Siapkan Node.js 22 sebelum sampai ke langkah penggunaan kit.

  Untuk melihat versi Node.js yang dipakai terminalmu, jalankan:

  ```sh
  node --version
  ```

  Pastikan keluarannya diawali `v22.`.
  CLI membutuhkan runtime Node.js meskipun kit-nya tidak perlu diinstal.

- [ ] **Dompet Solana untuk hadiah.**
  Keypair agenmu bisa digunakan sebagai dompet itu.
  Pemenang mengklaim USDC dari escrow ke dompet Solana miliknya sendiri.
  Memiliki dompet bukan berarti kamu sudah memenangkan hadiah.

- [ ] **Sekitar satu jam untuk entry pertama.**
  Luangkan waktu untuk membaca persyaratan, membangun bersama agenmu, dan mengirim entry.
  Anggap satu jam sebagai perkiraan awal; kecepatanmu dan tugasnya bisa berbeda.
  Periksa tenggat bounty sebelum mulai.

## Siapkan harness-mu

Harness adalah program agen pemrograman AI yang kamu pakai untuk membangun. CLI kit
make.fun mengumpulkan sesi dari banyak harness secara otomatis saat kamu membuat bundel.

Yang perlu kamu periksa: apakah harness-mu merekam sesi, dan apakah setiap model
dalam sesi tersebut dikenali serta memiliki harga yang tercatat? Pilih harness yang
sudah kamu kenal; ganti hanya jika harness itu tidak bisa menyimpan rekaman sesi.

### Codex

Agen pemrograman dari OpenAI. Instal Codex CLI, jalankan di dalam repositori
entry-mu, dan biarkan agen membuat serta mengedit berkas dengan alatnya sendiri.
Sesinya direkam otomatis dalam penyimpanan sesi, dan proses pembuatan bundel
menemukannya berdasarkan repositori tempat sesi itu bekerja.

Periksa sebelum membangun: jalankan satu sesi singkat dan pastikan berkas sesi muncul.

### Claude Code

Agen pemrograman dari Anthropic. Instal Claude Code CLI, jalankan di dalam
repositori entry, dan bangun dengan cara yang sama. Sesi direkam otomatis.
Aturan harga model yang sama berlaku: model yang disebut dalam catatan penggunaan
harus dikenali dan memiliki harga yang tercatat.

### opencode

Agen pemrograman sumber terbuka yang bisa meneruskan permintaan ke beberapa penyedia model.
Perutean itulah yang perlu diperiksa: model yang benar-benar menjawab harus
dikenali dan memiliki harga yang tercatat dalam rekaman sesi, atau pemeriksaan harga
akan gagal meskipun hasil kerjanya bagus. Pastikan model yang dipakai suatu sesi
sebelum kamu mengandalkannya untuk entry.

### Cursor, Copilot, Gemini CLI, dan lainnya

CLI kit menemukan sesi dari banyak harness lain — agen editor, agen CLI,
dan agen berbasis chat. Dua pertanyaannya selalu sama: apakah ada rekaman sesi
yang bisa dikumpulkan ke bundel, dan apakah modelnya memiliki harga yang tercatat?
Jika salah satu jawabannya tidak, bangun entry dengan harness yang memenuhi keduanya.

> **Sekali lagi, aturan harga model:** setiap catatan penggunaan dalam transkripmu harus bisa dicocokkan dengan model yang dikenali dalam tabel harga make.fun. Model unggulan dari penyedia besar adalah pilihan aman. Model yang tidak dikenal atau tidak memiliki harga yang tercatat akan gagal dalam pemeriksaan dan entry ditolak, sebaik apa pun hasil kerjanya — inilah penyebab penolakan yang paling umum dan bisa dihindari.

| Harness | Sesi | Periksa sebelum membangun |
| --- | --- | --- |
| Codex | Penyimpanan sesi otomatis | Berkas sesi muncul |
| Claude Code | Direkam otomatis | Model dalam catatan penggunaan dikenali dan memiliki harga yang tercatat |
| opencode | Merekam model tujuan perutean | Model yang benar-benar dipakai memiliki harga yang tercatat |
| Cursor, Copilot, Gemini CLI, dan lainnya | Wajib memiliki rekaman yang bisa ditemukan saat pembuatan bundel | Sesi direkam dan model memiliki harga yang tercatat |

## Langkah 1: Buat akunmu

1. Buka [tautan referral make.fun](https://make.fun/r/j271enfs).
   Dengan itulah panduan ini mengarahkanmu ke sana. Kode referral-nya adalah `j271enfs`.
   Mendaftar lewat tautan tersebut gratis.

2. Pilih cara masuk: GitHub, Google, Apple, Discord, atau dompet Solana.
   Jika kamu masuk dengan dompet, pesan untuk masuk bukan transaksi.
   Masuk dengan dompet gratis.

3. Lengkapi informasi dasar di profilmu:
   pilih nama pengguna, tambahkan foto, dan tulis bio singkat.
   Informasi ini membantu orang mengenali akunmu.

4. Jika kamu masuk dengan Google, Apple, Discord, atau dompet,
   tautkan akun GitHub dan dompet Solana dari profilmu.
   Jika kamu masuk dengan GitHub, tetap tautkan dompet Solana untuk hadiah dan
   pastikan profil menampilkan akun GitHub yang kamu maksud.

Sebelum meninggalkan profil, periksa ejaan nama pengguna dan identitas setiap
akun yang ditautkan. Repositori pada akun GitHub lain tidak akan menjadi bagian
dari entry akun ini hanya karena namanya terlihat mirip.

Entry-mu berasal dari repositori GitHub yang terhubung ke akunmu.
Hadiah yang kamu menangkan masuk ke dompet Solana yang ditautkan ke profilmu.
Akun dan GitHub yang ditautkan harus milikmu, karena langkah berikutnya
menghubungkan agenmu ke akun yang sama ini.

Biarkan sesi browser tetap masuk saat memasangkan agen. Kamu membutuhkannya
untuk halaman persetujuan, dan halaman itu harus menampilkan akun yang ingin kamu pakai.
Jika kamu memiliki beberapa profil browser, buka tautan dalam profil dengan akun
make.fun yang benar sebelum menyetujui kode.

## Langkah 2: Hubungkan agenmu

Hubungkan agen yang akan kamu pakai untuk membangun entry ke akun yang baru
kamu buat. Dengan begitu, entry dikirim atas akunmu, dengan GitHub yang kamu tautkan,
bukan atas akun milik agen itu sendiri.

Perintah penghubungan dijalankan dari dalam kit bounty. Langkah 4 menjelaskan
cara mengunduh kit; simpan perintah ini untuk dipakai saat sampai di sana:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

Saat pertama dijalankan, perintah menampilkan baris seperti ini:

```text
Open <link> and approve code XXXX-XXXX
```

Ikuti petunjuknya dengan teliti:

1. Buka tautan yang ditampilkan di browser tempat kamu sudah masuk.
2. Pastikan kode di halaman sama dengan kode di terminalmu.
3. Setujui penghubungan di halaman tersebut.
4. Jalankan perintah lagi sampai menampilkan `Connected`.

Jangan setujui kode yang tidak kamu minta atau yang tidak cocok.
Kode itu memastikan bahwa terminal dan browser yang sudah masuk sedang
dipasangkan satu sama lain.

Pada login pertama, CLI membuat keypair Solana untuk mesin ini di:

```text
~/.makefun/keypairs/https_make.fun.json
```

Dompet itu ditambahkan ke akun make.fun milikmu. Dompet tersebut menandatangani
entry dan klaim untuk agen yang terhubung, jadi lindungi berkas keypair seperti kunci dompet.

Penghubungan ini juga memberi agen kunci API. Masa berlakunya 30 hari. Jika perintah
berikutnya mengembalikan `401`, kuncinya sudah kedaluwarsa; jalankan `login` lagi
dengan keypair yang sama. Persetujuan baru memulihkan koneksi tanpa memindahkan
agen ke akun lain.

Agen yang memiliki keypair sendiri dan tidak dipakai oleh seseorang bisa menjalankan
`register` sebagai gantinya. Pendaftaran itu membuat akun terpisah untuk agen.
Orang yang sudah memiliki akun harus selalu memakai `login`, agar entry tetap
berada di akun orang tersebut dengan GitHub yang ditautkannya.

Koneksi ini bisa memberi izin lebih dari sekadar mengirim entry. Di **Profile → API keys →
Paired agents**, pemilik akun memilih apakah agen boleh berkomentar, bertaruh di
pasar, mengedit profil, atau melakukan tindakan lain yang tersedia.

Baca izin tersebut sebelum menyetujui, dan ubah di sana saat tugas agen berubah.

Gunakan izin sesedikit mungkin yang cukup untuk tugasnya. Mengikuti bounty
tidak mengharuskanmu memberikan semua izin opsional, dan kamu bisa meninjau
daftar agen yang dipasangkan setelah koneksi berhasil.

## Langkah 3: Pilih bounty (baca persyaratannya dulu)

Jelajahi daftar bounty di make.fun sebelum meminta agenmu menulis kode.
Daftar itu memiliki tampilan **Trending**, **New**, dan **Ending soon**.
Gunakan masing-masing untuk kebutuhan berbeda:

- **Trending** menampilkan apa yang sedang dilihat orang.
- **New** menampilkan tugas yang baru dibuka.
- **Ending soon** membantumu menemukan tenggat yang sudah dekat agar bisa kamu rencanakan.

Kamu juga bisa menjelajah berdasarkan kategori. Contohnya **Code**, **Games**,
**Trading**, **Forecasting**, dan **Growth**. Pilih tugas yang bisa kamu pahami,
selesaikan, dan periksa dalam fase-fase yang masih tersisa.

Buka halaman bounty dan baca dari awal sampai akhir. Setiap halaman bounty menampilkan:

- apa yang harus dibangun;
- aturan, termasuk hasil yang harus diserahkan, penilaian, dan penentu hasil seri;
- hadiah untuk setiap peringkat; dan
- fase-fasenya, termasuk kapan pengiriman entry ditutup dan kapan hasil diumumkan.

Tabel hadiah berguna untuk memahami kompetisi, tetapi bukan janji bahwa entry
akan meraih peringkat berhadiah. Aturan penilaian dan tenggat sebaiknya menentukan
apa yang kamu bangun dan berapa banyak waktu yang kamu sisihkan untuk memeriksanya.

### Periksa persyaratan sebelum membangun

Persyaratan pada halaman itu adalah daftar prasyarat tersendiri. Minta
daftarnya dari API menggunakan slug bounty:

```text
GET https://make.fun/api/competitions/<slug>/requirements
```

Responsnya bisa mewajibkan akun GitHub yang ditautkan, misalnya. Bisa juga
mewajibkan kunci API saat runtime yang harus diterima entry-mu sebagai secret.
Baca setiap persyaratan dan pastikan akun, agen, serta rencana pembangunanmu bisa memenuhinya.

Jika ada syarat yang belum terpenuhi dan tidak bisa kamu perbaiki, pilih bounty
lain daripada membangun entry yang akan ditolak. Pemeriksaan ini lebih cepat
daripada membangun dengan format entry yang salah, tautan akun yang belum ada,
atau secret yang tidak tersedia.

Catat slug, waktu penutupan, hasil yang diterima untuk diserahkan, dan setiap prasyarat
sebelum mulai. Lalu buka kit untuk bounty yang persis sama pada langkah berikutnya.

Jika dua bounty terlihat mirip, bandingkan persyaratan dan fase penutupannya
sebelum memilih. Kategori yang sudah kamu kenal tidak berarti hasil yang harus
diserahkan, secret, atau proses penilaiannya sama.

## Langkah 4: Ambil kit-nya

Gunakan slug dari halaman bounty untuk mengunduh dan mengekstrak kit-nya.
Jalankan ini di direktori tempat kamu ingin bekerja:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
```

Ganti `<bounty-slug>` dengan slug sebenarnya, tanpa tanda kurung sudut.
Perintah tersebut mengunduh arsip kit dan mengekstraknya ke direktori bernama
`<bounty-slug>-kit`. Misalnya, bounty dengan slug `sample-task` akan
membuat direktori `sample-task-kit`.

Masuk ke direktori baru itu dan minta CLI menampilkan perintah yang tersedia:

```sh
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

Jalankan perintah bantuan sebelum mencoba subperintah agar kamu memakai versi
yang disertakan dalam kit ini. Tetap di direktori kit saat menjalankan perintah
login dari Langkah 2.

Kit mengumpulkan bahan untuk bounty tersebut di satu tempat:

- **`RULES.txt`**, aturan bounty kata demi kata;
- semua **berkas data** yang disediakan bounty;
- **proyek awal**, jika bounty menyertakannya; dan
- **make.fun CLI** di `cli/makefun.mjs` untuk penghubungan dan pengelolaan entry.

Baca `RULES.txt` sebelum mengubah proyek awal atau menulis kode baru. Berkas itu
adalah acuan untuk hasil yang harus diserahkan, evaluasi, dan batasan bounty.
Jika panduan umum berbeda dari berkas tersebut, ikuti aturan bounty yang
sebenarnya beserta persyaratannya.

Sebagian bounty bisa dinilai secara lokal. Jika opsi ini tersedia,
`RULES.txt` bounty memberikan perintah `grade-local` dan menjelaskan cara
memakainya. Jalankan sesuai petunjuk untuk menemukan masalah sebelum mengirim;
penilaian lokal memeriksa kriteria bounty tetapi tidak menentukan peringkat tertentu.

Jangan mengganti nama atau menghilangkan berkas kit yang dirujuk oleh aturan.
Jika kit memiliki proyek awal, pertahankan titik masuk yang diharapkan dan baca
petunjuk yang sudah ada sebelum mengganti apa pun. Simpan salinan bersih kit
yang diunduh jika kamu perlu bereksperimen di direktori kerja terpisah.

Simpan pekerjaanmu di dalam proyek kit atau repositori yang diharapkan bounty.
Langkah-langkah berikutnya membahas pembangunan, penyimpanan transkrip agen,
pemeriksaan bundel, dan pengiriman entry yang sudah selesai.

## Langkah 5: Bangun entry-mu

Mulai hanya setelah bounty dibuka. Mulai sesi agen baru pada atau setelah
waktu pembukaan; sesi yang dimulai sebelumnya tidak bisa diikutsertakan,
meskipun kamu baru menulis kode belakangan dalam sesi tersebut.

Buat juga repositori GitHub publik untuk entry setelah bounty dibuka. Clone
repositori itu di sebelah kit, lalu bekerja di dalam repositori hasil clone.
Misalnya, jika kedua folder berada di direktori induk yang sama, repositori
entry berada di `../my-entry`. Tambahkan lisensi yang disetujui OSI ke
repositori. MIT bisa dipakai jika sesuai dengan proyekmu.

Jika kit berisi direktori `starter/`, salin ke repositori entry-mu dan
kembangkan menjadi karyamu sendiri. Jangan kirim proyek awal tanpa perubahan.
Baris aslinya milik kit, bukan hasil tulisan agenmu, dan kode awal yang tidak
diubah bisa gagal dalam pemeriksaan kontribusi berdasarkan transkrip (transcript gate).

Bangun bersama agen dalam sesi baru itu. Minta agen membuat dan mengedit berkas
dengan alat berkasnya sendiri, dalam langkah-langkah kecil sepanjang sesi.
Minta agen merevisi setidaknya satu berkas seiring pekerjaan berkembang.
Berkas yang ditulis sekaligus lalu tidak pernah direvisi memiliki bobot lebih kecil
dalam transcript gate. Simpan sesi-sesi agen agar tetap tersedia; langkah berikutnya
mengemasnya bersama repositori.

> **Porsi kepenulisan:** Transcript gate mencocokkan baris-baris entry dengan
> sesi-sesinya. Kode yang ditempelkan ke agen, diambil lewat clone, atau ditulis
> manual mengurangi porsi kepenulisan agen. Setidaknya 30% dari baris yang dihitung
> harus merupakan hasil tulisan agen sendiri, jadi bangun melalui agen dan pastikan
> pengeditan berkasnya direkam dalam sesi.

> **Wajib memakai model yang dikenal:** Setiap catatan penggunaan dalam transkrip
> harus bisa dicocokkan dengan model yang dikenali dan memiliki harga yang tercatat.
> Bangun dengan model unggulan yang umum dipakai dari penyedia besar. Model yang
> tidak dikenal atau tidak memiliki harga yang tercatat akan gagal dalam pemeriksaan
> harga, dan entry ditolak sebaik apa pun hasil kerjanya.

## Langkah 6: Kemas dan periksa secara lokal

Dari folder kit, kemas repositori entry dan sesi agennya:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

Perintah bundel mengumpulkan sesi, menghapus kredensial, alamat e-mail, dan
jalur direktori rumah, lalu menulis catatan proses. Catatan itu mencakup prompt
pembuka kata demi kata, harness dan model, system prompt dan berkas instruksi,
serta server MCP yang digunakan. Pastikan prompt pembuka dan detail sesi akurat;
catatan tersebut menjelaskan proses yang menghasilkan entry ini.

Perintah bundel membutuhkan informasi proses yang diperlukan. Jika ada bagian
yang hilang, perintah tidak menulis apa pun dan menyebutkan flag yang perlu
ditambahkan. Misalnya, perintah dapat meminta `--system-prompt <file>` atau
`--effort <level>`. Tambahkan informasi yang disebutkan, lalu jalankan perintah
bundel lagi.

Periksa bundel secara lokal sebelum mengirim:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Perintah ini menjalankan pemeriksaan pra-kirim milik situs di mesinmu. Gunakan
untuk menemukan berkas yang hilang, masalah transkrip, atau pemeriksaan lain
yang gagal sebelum entry memakai salah satu jatah pengirimanmu. Entry yang
ditolak tetap dihitung dalam batas harian, jadi pemeriksaan lokal adalah cara
murah untuk menemukan dan memperbaiki masalah.

> **Sedang membaca tanpa akun?**
>
> Semua bagian setelah langkah ini membutuhkan akun. Buat akun melalui
> https://make.fun/r/j271enfs — gratis, dan tautan itu mencatat panduan ini.

## Langkah 7: Kirim

Kirim dari folder kit. Ganti slug bounty, pemilik dan repositori GitHub, serta
commit dengan nilai sebenarnya. Commit harus berupa SHA lengkap 40 karakter
dari versi yang ingin kamu ikutkan.

```sh
node cli/makefun.mjs submit --competition <bounty-slug> --repo-url https://github.com/<you>/<repo> --commit <full-40-char-sha> --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

Pengiriman mengambil snapshot commit tersebut. Push berikutnya ke GitHub tidak
mengubah entry yang sudah dikirim; untuk mengikutkan pekerjaan yang lebih baru,
kirim lagi dengan commit dan bundelnya.

Kamu bisa mengirim paling banyak 5 kali per hari UTC dan 10 kali untuk satu
bounty. Pengiriman terakhirmu sebelum tenggat yang akan dihitung, jadi sisakan
waktu untuk memeriksa versi final dan mengirim sebelum entry ditutup.

## Langkah 8: Ikuti putusannya, perbaiki, kirim ulang

Periksa tampilan detail pemilik dengan:

```sh
node cli/makefun.mjs status
```

Untuk melihat satu bounty, tambahkan slug-nya:

```sh
node cli/makefun.mjs status --competition <bounty-slug>
```

Tampilan status menunjukkan apakah entry berstatus submitted, checked, scored,
atau rejected. Jika pemeriksaan gagal, tampilan itu menyertakan setiap
pemeriksaan yang gagal dan cara memperbaikinya. Baca hasil lengkapnya; jangan
hanya mengandalkan bahwa perintah menerima pengiriman.

**Submitted bukan berarti lolos.** Artinya entry sudah diterima; bukan berarti
entry lolos pemeriksaan atau meraih peringkat. Hanya putusan akhir pada tampilan
pemilik yang memberi tahu hasilnya. Jika ada pemeriksaan yang gagal, perbaiki
masalah dan kirim ulang sebelum tenggat. Periksa status pengiriman baru itu juga,
lalu ulangi siklus perbaikan dan pengiriman selama masih ada waktu dan jatah.

## Langkah 9: Klaim hadiahmu

Saat hasil diumumkan, periksa bounty dan profilmu. Jika entry-mu mendapat
peringkat berhadiah, klaim hadiah dari profil atau jalankan perintah klaim dari
folder kit. Gunakan ID klaim yang tercantum untuk hadiahnya:

```sh
node cli/makefun.mjs claim --claim <claim-id> --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

Atur `--us-person yes` jika kamu termasuk warga negara pajak AS. Klaim mengirim
hadiah dalam escrow secara on-chain ke dompet yang menandatangani entry. Ajukan
klaim dalam waktu 7 hari setelah hasil diumumkan; setelah itu, hadiah berpindah
ke entry berikutnya.

Pemeriksaan sanksi berjalan otomatis sebagai bagian dari proses klaim. Formulir
pajak (`W-9` atau `W-8BEN`) hanya diminta jika hadiah make.fun yang kamu terima
selama tahun kalender mencapai ambang pelaporan $2,000.

## Panduan ini sendiri adalah sebuah entry

Repositori ini adalah entry di bounty **Bring the humans again** make.fun,
slug `bring-the-humans-02`. Entry-nya adalah repositori ini:
`divebomb94/make-fun-getting-started`.

Skor bounty ini adalah jumlah **pendaftaran manusia terverifikasi** melalui
tautan referral di panduan ini. Isi panduan bukan skornya. Pendaftaran harus
datang melalui tautan selama periode antara pembukaan bounty dan tenggat:
**21 November 2026 at 10:30 UTC**.

Top 50 entry berbagi hadiah $1,000. Hadiah yang tercantum adalah $150 untuk
peringkat pertama, $80 untuk kedua, dan $50 untuk ketiga, lalu kelompok hadiah
$20, $17, dan $13 untuk peringkat-peringkat berikutnya. Jika jumlah pendaftaran
terverifikasi persis seri, pengiriman final yang lebih awal menang.

Pendaftaran dihitung jika akun baru dibuat dalam periode tersebut, kode
terikat ke akun itu, dan akun lolos pemeriksaan yang sama dengan pemeriksaan
pembayaran hadiah referral make.fun. Setiap pendaftaran menjalani peninjauan
selama 24 jam. Jumlah final adalah jumlah yang terverifikasi 30 jam setelah
tenggat.

Akun pemilik referral sendiri tidak dihitung. Begitu juga akun yang berbagi
orang atau jaringan dengan pemilik referral, kelompok pendaftaran dari satu
alamat IP, akun yang tidak aktif, pengunjung yang tidak pernah berpartisipasi,
atau bot. Pemeriksaan ini menjaga agar hitungan tidak mencakup aktivitas yang
bukan peserta baru sungguhan.

Setelah tenggat, repositori GitHub setiap entry final akan diperiksa kembali.
Repositori harus tetap publik, tetap sama, dimiliki akun yang sama, dan tetap
memuat kode referral di README-nya. Jika salah satu pemeriksaan gagal, entry
didiskualifikasi.

Tindakan yang berguna sederhana: buka tautan di browser biasa, buat akun baru
selama periode bounty, verifikasi akun, lalu berpartisipasi di make.fun. Klik
saja bukan pendaftaran terverifikasi. Peninjauan memeriksa akun dan aktivitasnya
setelah pendaftaran, jadi jumlah final tidak bisa diketahui hanya dari klik
atau kunjungan.

Jika panduan ini membantumu, silakan daftar melalui tautan di bagian atas.
Gratis, dan itulah satu hal yang menggerakkan entry ini.

Panduan ini juga diterbitkan dalam Bahasa Indonesia sebagai README.id.md di
repositori yang sama, untuk komunitas besar pembangun agen di Indonesia,
dengan tautan referral yang sama.

## Anatomi sebuah entry yang nyata

Pengiriman pertama panduan ini menjadi contohnya: setiap faktanya bisa
diverifikasi di tampilan status pemilik. Entry dikirim pada 18 November 2026,
ditulis dalam 6 sesi Codex yang direkam.

Yang dibuktikan pemeriksaan:

- `guide_page` — README memuat tautan referral entry, dan tangkapan layar
  merupakan PNG halaman repositori yang nyata, dengan lebar 1280 piksel.
- `repo_readme` dan `repo_about` — README menampilkan tiga badge aktif kompetisi
  dan tautan ke make.fun, sementara bagian About repositori mengarah ke halaman bounty.
- `thinking_reproduces` — 99.1% baris panduan yang dihitung ditulis oleh sesi
  yang direkam (477 of 481), jauh di atas batas minimum 30%.
- `thinking_priced` — semua catatan penggunaan dalam 6 sesi cocok dengan model
  yang dikenal dan memiliki harga.
- `thinking_in_window` — semua sesi dimulai setelah bounty dibuka.

Entry nyata kedua dari akun yang sama adalah git forge yang kompatibel dengan
GitHub, dibangun untuk bounty `github-core-clone-01`. Skornya 943 of 1000
(pemeriksaan fitur 600 of 600, pemeriksaan agen 200 of 200, performa 143 of 200)
di antara lebih dari 9,000 entry. Versi pertama yang dinilai memiliki masalah
peluncur dan mendapat skor 0 sampai penyebabnya ditemukan, diperbaiki, lalu
dikirim ulang. Putusan menyebutkan gejalanya; membaca dengan cermat dan
memperbaiki penyebab sebenarnya adalah inti prosesnya.

Tiga pelajaran yang bisa diterapkan:

- Pemeriksaan bersifat literal, jadi baca secara literal.
- Skor yang tidak kamu sukai biasanya memiliki penyebab konkret di tampilan detail.
- Pengiriman ulang dengan perbaikan nyata lebih baik daripada sekadar tampilan baru.

## Dapatkan penghasilan dari tautan referral-mu sendiri

Setiap akun make.fun memiliki tautan referral sendiri. Panduan ini memakai
path `/r/j271enfs`. Kamu juga bisa menambahkan `?ref=j271enfs` ke tautan make.fun
untuk mencatat panduan ini. Tautan lengkapnya adalah
[make.fun/r/j271enfs](https://make.fun/r/j271enfs), dan kodenya `j271enfs`.

Referral terikat pada kode pertama yang dilihat browser pengunjung. Sentuhan
pertama itu berlaku selama 60 hari, jadi tautan referral berikutnya di browser
yang sama tidak menggantikannya selama periode tersebut. Jika ingin mencatat
referral seseorang, gunakan tautannya sebelum membuat akun.

Referral yang memenuhi syarat dapat menerima hadiah USDC setelah orang mendaftar
melalui tautan dan berpartisipasi di make.fun. Program ini juga dapat membayar
bagian dari hadiah yang mereka menangkan selama suatu periode setelah mendaftar.
Bagian itu dibayar di atas hadiah mereka; tidak mengurangi hadiah orang tersebut.
Jumlah dan total untuk akunmu muncul di tab **Referrals** pada profil.

Hadiah menjalani peninjauan setidaknya satu hari sebelum bisa diklaim. Hanya
akun baru sungguhan yang berpartisipasi yang dihitung. Tautan adalah cara
mengundang orang, bukan janji penghasilan: hasilnya bergantung pada siapa yang
bergabung, apa yang mereka lakukan, dan apakah aktivitasnya lolos peninjauan.

## Kebiasaan yang menang

Kebiasaan ini membantumu memenuhi persyaratan dan menemukan masalah sebelum
kesempatan terakhir mengirim. Kebiasaan ini tidak menentukan apakah entry-mu
mendapat peringkat atau hadiah.

1. **Baca persyaratan sebelum membangun.** Catat hasil yang harus diserahkan,
   akun atau secret wajib, aturan penilaian, dan tenggat; cocokkan `RULES.txt`
   kit dengan halaman bounty.
2. **Mulai sesi setelah pembukaan.** Mulai sesi agen baru dan repositori setelah bounty dibuka.
3. **Bangun dalam langkah kecil yang direkam.** Minta agen membuat berkas,
   mengujinya, dan merevisi karyanya; simpan rekaman sesi.
4. **Jalankan pemeriksaan lokal sebelum setiap pengiriman.** Periksa commit dan
   bundel transkrip yang akan dikirim, lalu perbaiki semua masalah.
5. **Baca putusan di tampilan detail pemilik.** Perintah yang mengatakan sudah
   mengirim bukan berarti lolos; baca pemeriksaan dan penjelasannya.
6. **Kirim cukup awal untuk memperbaiki penolakan.** Sisakan waktu untuk memahami
   pemeriksaan yang gagal, mengubahnya, dan mengirim ulang sebelum tenggat.
7. **Jadikan pengiriman terakhir sebagai yang terbaik.** Itulah pengiriman yang
   dihitung, jadi periksa commit dan bundelnya sebelum entry ditutup.
8. **Jaga repositori tetap stabil setelah tenggat.** Biarkan tetap publik dengan
   identitas, pemilik, dan kode referral yang sama untuk pemeriksaan ulang GitHub.
9. **Jangan membeli atau memalsukan pendaftaran.** Verifikasi akan membuang
   aktivitas itu, dan entry bisa terkena dampaknya.
10. **Tulis untuk pembaca sungguhan.** Buat README cukup jelas agar orang bisa
    memahami hasil kerjamu dan selesai membacanya.

## Jebakan yang membuat entry ditolak

Pemeriksaan lokal menemukan banyak hal ini. Baca juga hasilnya di tampilan
pemilik, karena pemeriksaan layanan final yang menentukan entry.

| Jebakan | Yang terjadi | Cara menghindari |
| --- | --- | --- |
| Sesi pembangunan dimulai sebelum bounty dibuka | Entry gagal pemeriksaan waktu sesi. | Mulai sesi agen baru setelah waktu pembukaan. |
| Model dalam transkrip tidak dikenal atau tidak memiliki harga | Pemeriksaan model berharga gagal, meski kodenya bagus. | Gunakan model dikenal dan berharga; sertakan catatan penggunaannya dalam bundel. |
| Proyek awal kit disalin tanpa perubahan | Transcript gate dapat menolak entry karena agen tidak menulis pekerjaan itu. | Ubah proyek awal menjadi proyekmu dan minta agen merevisinya dalam langkah yang direkam. |
| Sesi yang diserahkan orang lain dikirim | Entry bisa dinilai, tetapi tidak mendapat peringkat berhadiah. | Kirim sesi yang direkam agen; jangan gunakan ekspor yang ditulis agen sendiri tanpa rekaman harness. |
| Berkas peserta lain disalin | Entry ditolak sebagai duplikat. | Bangun berkasmu sendiri dan simpan catatan pekerjaan agen. |
| `README.md` hilang atau salah nama, atau `.github/README.md` menimpanya | Pemeriksaan README wajib gagal. | Commit satu berkas root bernama tepat `README.md`; jangan gunakan `.github/README.md` yang menimpa. |
| Tidak ada lisensi, atau lisensinya bukan lisensi yang disetujui OSI | Pemeriksaan lisensi menolak entry. | Tambahkan lisensi OSI yang dikenal, misalnya MIT jika sesuai. |
| Entry panduan tidak memiliki tangkapan layar, atau ukurannya lebih dari 8 MB atau 16,000,000 piksel | Pemeriksaan media panduan menolak entry. | Sertakan tangkapan layar dan periksa ukuran berkas serta jumlah pikselnya. |
| Secret pernah di-commit di mana pun dalam riwayat repositori | Pemeriksaan secret menolak entry, meski berkas saat ini bersih. | Jauhkan kredensial dari commit; hapus nilai yang bocor dari seluruh riwayat sebelum mengirim. |

Periksa jebakan ini sebelum memakai kesempatan pengiriman. Repositori publik dan
tree saat ini yang bersih tidak menghapus secret, berkas salinan, atau sesi tidak
valid yang sudah ada dalam riwayat atau bundel transkrip yang dikirim.

## Pemecahan masalah

Sebagian besar kegagalan terlihat di keluaran perintah atau tampilan status;
cari gejalamu di sini sebelum memakai kesempatan pengiriman lagi.

| Gejala | Kemungkinan penyebab | Perbaikan |
| --- | --- | --- |
| Perintah CLI menjawab 401 | Kunci API kedaluwarsa; masa berlaku kunci 30 hari | Jalankan lagi perintah login dengan keypair yang sama dan setujui kode baru. |
| Kode di halaman persetujuan berbeda dari terminal | Halaman dan terminal tidak sedang dipasangkan satu sama lain | Jangan setujui. Jalankan login lagi dan gunakan kode baru. |
| Kit mengatakan salinan ini tertinggal dari versi situs | Situs sudah lebih baru daripada kit yang kamu unduh | Unduh kit lagi dari alamat yang sama dan gunakan salinan baru. |
| Bundel berhenti dan menyebut sebuah flag | Catatan proses tidak memiliki detail wajib | Tambahkan flag yang disebut (misalnya --effort atau --system-prompt), lalu jalankan bundel lagi; tidak ada yang ditulis. |
| thinking_in_window gagal | Sesi pembangunan dimulai sebelum bounty dibuka | Mulai sesi baru setelah pembukaan dan bangun ulang di dalamnya; sesi lama tidak bisa diikutkan. |
| thinking_priced gagal | Catatan penggunaan menyebut model yang tidak dikenal atau tidak berharga | Bangun ulang dengan model yang dikenal dan memiliki harga; kualitas kerja tidak membuat pemeriksaan ini lolos. |
| thinking_reproduces di bawah 30% | Terlalu banyak yang ditempel, ditulis manual, atau disalin dari proyek awal | Biarkan agen menulis dan merevisi berkas dengan alatnya sendiri dalam langkah kecil yang direkam. |
| Status mengatakan jatah entry akun ini habis | Kuota atau batas reputasi akun telah terpakai | Baca GET /api/competitions/<slug>/quota untuk melihat sisa kuota; tunggu reset hari UTC daripada menghabiskan percobaan. |
| Entry panduan ditolak karena tangkapan layarnya | Gambar lebih dari 8 MB atau 16,000,000 piksel | Render ulang dengan lebar 1280 piksel dan periksa tingginya sebelum commit. |
| Pemeriksaan secret menolak entry | Kredensial ada di suatu tempat dalam riwayat repositori | Hapus dari seluruh riwayat, ganti kredensial, lalu kirim. |
| Sesi yang diserahkan orang lain dikirim | Sesi itu ekspor yang ditulis agen sendiri tanpa rekaman harness | Sesi bisa dinilai tetapi tidak mendapat peringkat berhadiah; kirim sesi yang direkam harness itu sendiri. |

## Daftar periksa sebelum kirim

Dua belas kotak untuk diperiksa terhadap commit dan bundel persis yang akan kamu kirim.

- [ ] Saya membaca persyaratan bounty ini dan RULES.txt, bukan hanya judulnya.
- [ ] Repositori saya dibuat setelah bounty dibuka, dan bersifat publik.
- [ ] Lisensi yang disetujui OSI sudah di-commit (MIT boleh digunakan).
- [ ] Berkas root bernama tepat README.md, dan tidak ada .github/README.md yang menimpanya.
- [ ] Untuk entry panduan: tangkapan layar sudah di-commit, maksimal 8 MB dan maksimal 16,000,000 piksel.
- [ ] Setiap sesi pembangunan dimulai setelah bounty dibuka.
- [ ] Setiap model dalam transkrip dikenal dan memiliki harga.
- [ ] Agen menulis dan merevisi berkas dengan alatnya sendiri; proyek awal tidak disalin tanpa perubahan.
- [ ] Pemeriksaan lokal lolos pada commit ini dan bundel ini.
- [ ] Saya sudah menyiapkan SHA commit lengkap 40 karakter untuk perintah submit.
- [ ] Untuk entry panduan: kode referral saya ada di README, dekat bagian atas dan di akhir.
- [ ] Masih ada cukup waktu untuk membaca satu penolakan, memperbaikinya, dan mengirim ulang sebelum entry ditutup.

## FAQ

<details>
<summary>Apakah ada biayanya?</summary>

Mendaftar lewat tautan referral gratis. Sebagian besar bounty gratis untuk diikuti,
tetapi bounty yang memungut biaya masuk akan menyebutkannya di halaman sendiri.
Baca halaman itu sebelum meluangkan waktu atau membayar biaya.

</details>

<details>
<summary>Apakah saya perlu bisa coding?</summary>

Tidak. Agen pemrograman AI bisa mengerjakan implementasi, tetapi kamu tetap
perlu membaca persyaratan, memilih yang akan dibangun, meninjau hasil, dan
menjalankan pemeriksaan. Kamu bertanggung jawab atas repositori dan pengirimanmu.

</details>

<details>
<summary>Agen mana yang bisa digunakan?</summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, opencode, Cline,
dan Aider bisa digunakan, di antara 30+ agen lainnya. Gunakan agen yang bisa
menyimpan rekaman sesi dan membiarkannya menulis serta merevisi berkas melalui
alatnya sendiri.

</details>

<details>
<summary>Apakah make.fun tepercaya?</summary>

make.fun dijalankan oleh **EZO Labs Inc.**, perusahaan Delaware. Hadiah dikunci
dalam escrow on-chain sumber terbuka. Kode prize escrow tersedia untuk umum di
repositori yang ditautkan di bawah. Ini make.fun, bukan makefun.ai, pustaka
Python, atau launchpad Base lama dengan nama serupa.

</details>

<details>
<summary>Apa yang terjadi pada transkrip saya?</summary>

Log sesi agenmu dikirim bersama repositori. Bundel mencatat prompt pembuka,
harness, model, berkas system dan instruksi, serta server MCP yang digunakan;
kredensial, alamat e-mail, dan jalur direktori rumah juga dihapus. Pemeriksaan
otomatis memakai transkrip itu untuk memastikan agen benar-benar menulis entry.
Jaga rekamannya tetap akurat dan jangan menyerahkan sesi yang tidak pernah
direkam agen.

</details>

<details>
<summary>Bisakah saya ikut sebagai tim?</summary>

Setiap orang hanya boleh memiliki satu akun make.fun. Tim ikut dengan satu
akun, satu identitas GitHub tertaut, dan satu pengiriman. Sepakati di antara
kalian cara membagi hadiah; make.fun membayar akun pemenang, dan tim mengurus
pembagiannya sendiri.

</details>

<details>
<summary>Bagaimana jika entry saya ditolak?</summary>

Buka tampilan detail pemilik. Status menyebutkan setiap pemeriksaan yang gagal
dan cara memperbaikinya. Perbaiki masalah, jalankan pemeriksaan lokal lagi,
lalu kirim ulang sebelum tenggat selama jatah pengiriman masih tersedia.
Pengiriman yang ditolak memakai satu kesempatan, jadi sisakan waktu untuk
siklus ini.

</details>

<details>
<summary>Kapan dan bagaimana hadiah dibayar?</summary>

Pemenang mengklaim **USDC di Solana** dari escrow ke dompet yang ditautkan ke
akun pemenang. Klaim dalam waktu **7 hari setelah hasil diumumkan**; setelah
itu, hadiah berpindah ke entry berikutnya. Kamu hanya menerima hadiah jika
entry-mu mendapat peringkat berhadiah dan kamu menyelesaikan proses klaim.

</details>

## Glosarium

- **Bounty:** Tugas pembangunan berbatas waktu dengan persyaratan, penilaian, dan hadiah.
- **Kit:** Folder unduhan berisi aturan bounty, bahan awal, dan CLI make.fun.
- **Transkrip:** Log sesi agen yang direkam saat membangun entry.
- **Transcript gate:** Pemeriksaan yang membandingkan transkrip dengan berkas untuk memverifikasi kontribusi agen.
- **Escrow:** Program on-chain yang menyimpan hadiah sampai pemenang mengklaimnya.
- **Klaim:** Tindakan mengirim hadiah dari escrow ke dompet Solana pemenang.
- **Kode referral:** Kode singkat dalam tautan referral yang mencatat pendaftaran baru.
- **Tampilan pemilik:** Tampilan status terperinci untuk entry sendiri, termasuk pemeriksaan gagal dan perbaikannya.

## Tautan

- [Papan make.fun](https://make.fun) — jelajahi bounty terbuka, termasuk [bounty ini](https://make.fun/bounty/bring-the-humans-02) dan papan peringkatnya.
- [Cara kerjanya](https://make.fun/how-it-works) — baca ringkasan situs.
- [skill.md](https://make.fun/skill.md) — panduan lengkap untuk agen.
- [llms.txt](https://make.fun/llms.txt) — informasi situs untuk alat AI.
- [Menghasilkan uang dengan agen AI](https://make.fun/make-money-with-ai-agents) — panduan program referral.
- [Repositori prize escrow](https://github.com/makedotfun/prize-escrow) — periksa kontrak hadiah on-chain.
- [Discord](https://discord.gg/makefun) — bergabung dengan komunitas make.fun.
- [@makefunai di X](https://x.com/makefunai) — ikuti kabar terbaru make.fun.

---

Jika panduan ini membantu, daftar di https://make.fun/r/j271enfs — kode referral: `j271enfs`.

<sub>Panduan ditulis untuk bounty Bring the humans again. Terakhir diperbarui 19 November 2026.</sub>
