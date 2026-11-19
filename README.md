# Katalog Produk (JavaFX)

Aplikasi katalog produk berbasis **JavaFX** yang terhubung ke database relasional untuk mengelola data produk (tambah, lihat, ubah/edit, dan hapus).

## Fitur Utama

* **Lihat Katalog Produk**: Menampilkan daftar produk dalam bentuk kartu (`TilePane`) lengkap dengan gambar, nama, harga, dan ID produk.
* **Tambah Produk**: Menambahkan produk baru (nama, harga, dan pilihan foto) ke database.
* **Edit Produk**: Memilih kartu produk pada katalog untuk memuat ulang datanya ke form input, mengubah informasi produk, lalu memperbaruinya ke database.
* **Hapus Produk**: Menghapus produk yang dipilih dari database dan menyegarkan tampilan katalog secara otomatis.

## Cara Menggunakan

* **Tambah**: Isi *Nama produk*, *Harga (Rp)*, dan pilih *Foto contoh*, lalu klik **Simpan**.
* **Edit**: Klik salah satu kartu produk di katalog agar datanya muncul di form, ubah isian yang diinginkan, lalu klik **Edit**.
* **Hapus**: Klik kartu produk yang ingin dihapus, lalu klik **Hapus**.

## Tampilan Produk
![Tampilan Katalog Produk](KatalogProduk/src/main/resources/image/TampilanKatalogProduk.png)
