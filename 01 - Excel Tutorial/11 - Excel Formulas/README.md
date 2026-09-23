
# 11 - Excel Formulas (Relatif vs Absolut)

Materi pembelajaran mengenai perbedaan referensi sel di Excel, yaitu sel Relatif yang bisa bergeser otomatis dan sel Absolute yang dikunci mati menggunakan simbol dolar ($).

## 1. Referensi Relatif (Relative Reference)

Secara default, semua rumus di Excel itu sifatnya relatif.

* **Cara Kerja**: Kalau rumus dicopy ke baris atau kolom lain, posisi sel di dalam rumus bakal ikut bergeser secara otomatis.
* **Contoh**: Jika rumus `=A1+B1` digeser ke bawah satu baris, otomatis berubah menjadi `=A2+B2`.

## 2. Referensi Absolut (Absolute Reference)

Digunakan ketika kita ingin mengunci posisi sel tertentu agar **tidak ikut bergeser** meskipun rumusnya dicopy ke mana-mana.

* **Simbol Pengunci**: Menggunakan tanda dolar (`$`) sebelum huruf kolom dan angka baris.
* **Contoh Penulisan**: `$A$1` (Kolom A dan baris 1 dikunci total).
* **Shortcut Cepat**: Cukup tekan tombol **F4** di keyboard saat mengetik nama sel untuk langsung menambahkan tanda `$`.

## 3. Contoh Implementasi Kasus

* **Relatif**: Menghitung total harga per barang di tabel penjualan (baris ke bawah terus berubah sesuai baris produknya).
* **Absolut**: Mengalikan daftar harga barang dengan satu angka pajak tetap atau kurs konversi mata uang yang posisinya cuma ada di satu sel khusus (misal sel `C1` dikunci jadi `$C$1` supaya waktu rumusnya ditarik ke bawah, patokannya nggak lari-lari).
