
# 15 - Excel Parentheses (Tanda Kurung)

Materi mengenai penggunaan tanda kurung `()` dalam rumus Excel untuk mengatur urutan prioritas perhitungan matematika (PEMDAS/BODMAS).

## Apa itu Parentheses?

* **Definisi**: Tanda kurung `()` yang digunakan di dalam rumus Excel untuk mendikte **bagian mana yang harus dihitung lebih dulu**.
* **Fungsi Utama**: Mengubah aturan standar prioritas matematika bawaan Excel (di mana perkalian/pembagian biasanya dikerjakan sebelum penjumlahan/pengurangan).

## Kenapa Sangat Penting?

Tanpa tanda kurung, Excel akan menghitung perkalian/pembagian lebih dulu secara otomatis.

* **Contoh Tanpa Kurung**: `=5 + 2 * 3`
  * Excel akan menghitung `2 * 3 = 6`, lalu ditambah `5`. Hasil akhirnya: **11**.
* **Contoh Dengan Kurung**: `=(5 + 2) * 3`
  * Excel akan menghitung yang di dalam kurung dulu `5 + 2 = 7`, lalu dikali `3`. Hasil akhirnya: **21**.

## Aturan Dasar

* Setiap ada kurung buka `(`, wajib ada kurung tutup `)`. Kalau tidak seimbang, Excel akan memunculkan pesan *error*.
* Tanda kurung bisa disarangkan (kurung di dalam kurung) untuk rumus yang lebih kompleks.
