
# 12 - Excel Relative Reference

Materi khusus mengenai penggunaan referensi sel relatif (Relative Reference) di Excel.

## Apa itu Relative Reference?

* **Definisi**: Referensi sel (seperti `A10` atau `B10`) yang sifatnya fleksibel dan akan **bergeser atau menyesuaikan secara otomatis** saat rumusnya disalin atau ditarik ke baris/kolom lain.
* **Karakteristik**: Tidak menggunakan simbol dolar (`$`) sama sekali dalam penulisan alamat selnya.

## Cara Kerja & Simulasi

Saat rumus relatif ditarik ke bawah pada sebuah tabel:

* Baris di dalam rumus akan otomatis turun mengikuti baris data pasangannya.
* **Contoh Kasus**: Menghitung total harga (`Jumlah x Harga Satuan`).
  * Di baris 10: `=A10 * B10`
  * Ditarik ke baris 11 otomatis berubah jadi: `=A11 * B11`
  * Ditarik ke baris 12 otomatis berubah jadi: `=A12 * B12`

## Kapan Digunakan?

* Digunakan ketika kita ingin melakukan perhitungan baris demi baris secara sejajar dan berpasangan tanpa harus mengetik rumus satu persatu secara manual.
