# 16 - Excel Functions Intro (Pengenalan Fungsi Excel)

Materi pengenalan mengenai *functions* (fungsi bawaan) di Excel untuk memproses data secara instan tanpa rumus manual yang panjang.

## Apa itu Excel Functions?

* **Definisi**: Rumus siap pakai yang sudah disediakan oleh Excel untuk melakukan perhitungan tertentu (seperti penjumlahan otomatis, nilai rata-rata, pencarian data, dll.).
* **Struktur Penulisan (Syntax)**:

  ```excel
  =NAMA_FUNGSI(argumen1, argumen2, ...)
  ```
* Selalu diawali dengan tanda sama dengan (`=`).
* Diikuti nama fungsi (biasanya huruf kapital, misal `SUM`, `AVERAGE`).
* Di dalam tanda kurung adalah **argumen** (bisa berupa rentang sel/range, misal `A3:A10`).

## Perbedaan Formula vs Function

* **Formula** : Rumus buatan sendiri menggunakan operator matematika manual.
* *Contoh* : `=A1 + A2 + A3 + A4 + A5` (Capek kalau datanya ada 100 baris!).
* **Function** : Rumus instan bawaan Excel yang merangkum formula panjang.
* *Contoh* : `=SUM(A1:A5)` (Jauh lebih cepat, rapi, dan anti-ribet).

## Contoh Fungsi Dasar yang Sering Dipakai:

* `=SUM(range)`: Menjumlahkan seluruh angka dalam satu rentang sel.
* `=AVERAGE(range)`: Mencari nilai rata-rata.
* `=MAX(range)`: Mencari angka paling besar.
* `=MIN(range)`: Mencari angka paling kecil.
