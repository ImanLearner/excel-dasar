
# 04 - Excel Syntax

Memahami sintaks penulisan formula dinamis menggunakan koordinat alamat cell (Cell Reference).

## 1. Hardcoded vs Cell Reference

* **Hardcoded (`=20+30`):** Angka diketik mati di dalam rumus. Jika data di tabel berubah, rumus harus diedit ulang secara manual.
* **Cell Reference (`=A1+B1`):** Rumus membaca koordinat cell sebagai variabel. Jika nilai angka di cell `A1` atau `B1` diganti, hasil perhitungan otomatis langsung ter-update (bersifat dinamis).

## 2. Struktur Dasar Sintaks

* Selalu diawali dengan tanda sama dengan (`=`).
* Menggabungkan koordinat cell dengan operator aritmatika dasar (`+`, `-`, `*`, `/`).
* Tidak peka huruf kapital (bisa mengetik `=a1+b1` atau `=A1+B1`).

## 3. Latihan Praktik

1. Buka file `syntax.xlsx` di Microsoft Excel.
2. Masukkan angka `20` di cell `A1`.
3. Masukkan angka `30` di cell `B1`.
4. Di cell `C1`, ketik rumus `=A1+B1` lalu tekan **Enter** (hasilnya akan muncul `50`).
5. Coba ubah angka pada cell `A1` menjadi `100`, lalu amati apakah hasil di cell `C1` otomatis berubah menjadi `130`.
