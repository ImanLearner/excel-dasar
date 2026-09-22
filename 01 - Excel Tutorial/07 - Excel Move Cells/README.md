# 07 - Excel Move Cells

Materi pembelajaran Excel mengenai dasar-dasar perhitungan otomatis menggunakan operator aritmatika dan fungsi agregat bawaan.


## 1. Aturan Dasar Formula

* Semua rumus di Excel **wajib diawali dengan tanda sama dengan (`=`)**. Jika tidak pakai `=`, Excel hanya akan membacanya sebagai teks biasa.
* Menggunakan operator aritmatika standar:
  * Penjumlahan: `+` (Contoh: `=A1+B1`)
  * Pengurangan: `-` (Contoh: `=A1-B1`)
  * Perkalian: `*` (Contoh: `=A1*B1`)
  * Pembagian: `/` (Contoh: `=A1/B1`)
  * Pangkat: `^` (Contoh: `=A1^2`)

## 2. The Big 5 (Fungsi Agregat Utama)

Fungsi bawaan Excel yang paling sering digunakan untuk meringkas data operasional:

* **`=SUM(range)`**: Menjumlahkan seluruh angka dalam rentang sel tertentu. (Contoh: `=SUM(A1:A10)`)
* **`=AVERAGE(range)`**: Menghitung nilai rata-rata dari sekumpulan data. (Contoh: `=AVERAGE(A1:A10)`)
* **`=COUNT(range)`**: Menghitung jumlah sel yang hanya berisi data angka.
* **`=MAX(range)`**: Mencari nilai tertinggi / maksimal dari sekumpulan data.
* **`=MIN(range)`**: Mencari nilai terendah / minimal dari sekumpulan data.

## 3. Formula vs Function

* **Formula:** Rumus manual buatan sendiri menggunakan operator dasar (Contoh: `=(A1+A2+A3)/3`).
* **Function:** Nama rumus siap pakai bawaan Excel yang jauh lebih cepat dan efisien (Contoh: `=AVERAGE(A1:A3)`).
