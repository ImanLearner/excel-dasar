# 10 - Excel Basic Formulas (`SUM`, `AVERAGE`, `COUNT`)

Materi pembelajaran mengenai fungsi-fungsi dasar matematika dan statistika otomatis di Excel untuk mengolah data angka secara cepat.

## 1. Struktur Dasar Rumus & Fungsi

Sintaks standar penulisan fungsi dasar di Excel:

=SUM(A1;A10) atau =SUM(A1:A10)

* **Nama Fungsi**: Menggunakan fungsi seperti `SUM`, `AVERAGE`, atau `COUNT`.
* **Titik Koma (`;`)**: Digunakan sebagai pemisah argumen/rentang sel sesuai pengaturan regional.
* **Titik Dua (`:`)**: Digunakan untuk menunjukkan rentang data (*range*), contohnya dari sel A1 sampai A10.

## 2. Penjelasan Fungsi Utama

* **`SUM`**: Digunakan untuk **menjumlahkan** seluruh angka di dalam rentang sel tertentu.
* **`AVERAGE`**: Digunakan untuk mencari **nilai rata-rata** dari sekumpulan data angka.
* **`COUNT`**: Digunakan untuk **menghitung jumlah sel** yang berisi angka di dalam rentang tertentu.

## 3. Contoh Implementasi Kasus

* Menghitung total nilai atau total angka log secara otomatis:

```
  =SUM(A1:A10)
```

* Mencari rata-rata dari suatu rentang data:

```
=AVERAGE(A1:A10)
```

* Menghitung jumlah sel berisi angka:

```
=COUNT(A1:A10)
```
