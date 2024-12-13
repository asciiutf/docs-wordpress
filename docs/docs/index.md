---
title: Beranda

---

# Dokumentasi Pengembangan WordPress Bahasa Indonesia

WordPress salah satu _Content Management System (CMS)_ paling populer didunia. Menjadi pilihan utama, selain mudah digunakan juga karena mempunyai kapabilitas untuk dikembangan sesuai kebutuhan. Didalam dokumentasi ini Anda akan mempelajari pengembangan WordPress secara komprehensif.

## Sekilas

WordPress cepat, ringan, modular dan sangat mudah digunakan jika dibandingkan dengan CMS lain. Untuk menjaga nilai-nilai tersebut Tim Inti _(Core Team)_ setiap menambahkan fungsionalitas baru selalu dipertimbangkan dengan seksama.

Pada banyak kasus pengguna sering kali perlu fungsi tambahan untuk membuatnya tetap sejalan dengan kebutuhan. Katakan pada bisnis logistik Anda membutuhan sistem pelacakan paket sederhana.

!!! warning "Aturan"

    Meskipun memungkinkan mengubah file inti WordPress yang telah Anda unduh untuk menambahkan fungsi baru, tetapi tindakan tersebut **tidak dibenarkan!**.

    Kenapa? Jika WordPress merilis versi baru katakan perbaikan bugs, maka Anda akan kesulitan untuk melakukan update - semua file yang telah dirubah akan tergantikan dengan file versi terbaru dari WordPress. Dengan demikian Anda diharuskan mengembalikan file yang telah dirubah agar fungsi tambahan dapat digunakan kembali.

    Tentu saja praktik tersebut sangat menyulikan dan membuang waktu berharga Anda.

Cara yang benar menambahkan fungsi baru di WordPress antara lain menggunakan kostum Plugin dan Tema.

## Memulai

- **[Standar Koding](standar-koding/1.1-index.md)** - Bagaimana standar koding yang benar di WordPress.
- **Membuat Plugin** - Pelajari bagaimana membuat plugin WordPress dengan benar.
- **Mempublikasikan Plugin** - Sebarkan plugin ke semua pengguna WordPress. Jika memungkinkan, hasilkan uang dengan menjualnya.
- **Membuat Tema** - Pelajarai bagaimana membuat tema WordPress dengan benar.
- **Mempublikasikan Tema** - Sebarkan tema ke semua pengguna WordPress.
- **Debugging** - Referensi dan panduan menggunakan kemampuan debugging bawaan WordPress.
- **Validasi Data** - Setiap pengembang WordPress **wajib** mengetahui ini. Pelajari bagaimana memproses data yang benar untuk memastikan keamanan paling mendasar seperti pencegahan SQL Injection.
- **Pembaruan Plugin dan Tema** - Referensi bagaimana agar plugin dan tema selalu kompatibel dengan semua versi WordPress.
- **Referensi `function`** - Kumpulan fungsi-fungsi PHP _re-usable_ yang tersedia di WordPress.
- **Variabel Global** - Daftar variable default WordPress dan bagaimana merubahnya sesuai kebutuhan.
- **Post Type** - Salah satu _building-block_ WordPress adalah _Post Type_. Memungkinkan Anda membuat beragam jenis post. WooCommerce memanfaatkan ini untuk memmbuat Produk.
- **Taxonomy** - Membuat taksonomi baru tanpa merubah defaultnya WordPress.
- **Shortcode** - Potongan kode yang dapat digunakan dimana saja, pelajari cara membuatnya.
- **Reversed Terms** - Semua istilah yang telah digunakan di WordPress, jangan mendefinisikannya lagi di kode yang Anda tulis.

## APIs

- **Plugin API** - Menggunakan Hooks, Actions dan Filters di plugin atau tema.
- **Dashboard Widget API** - Tambahkan fungsi monitoring baru (misal Google Analytics) kedalam halaman Admin WordPress. Pelajari bagian ini.
- **Settings API** - Referensi dengan beberapa contoh menambahkan atau merubah di halaman pengaturan.
- **Options API** - Referensi bagaimana menyimpan pengaturan.
- **Transients API** - Referensi cara menyimpan data sementara dan menggunakannya, seperti Cache.
- **Widgets API** - Bagaimana menambahkan widget baru ke sidebar. Umumnya digunakan dalam pengembangan tema.
- **Quicktags API** - Referensi menambahkan kostum tombol ke editor HTML (bukan CKEditor).
- **Rewrite API** - Pelajari bagaimana cara kerja URL atau _routing_.
- **API Kostumasi Tema** - Detail mengenai _Theme Customization Screen_.
- **Filesystem API** - Referensi bagaimana menangani file seperti cara menerima upload file yang aman dari _user_ (pengunjung website).
