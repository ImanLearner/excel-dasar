
# 08 - Excel Logical Functions (`IF` Dasar)

Materi pembelajaran Excel mengenai penggunaan fungsi logika kondisional (`IF`) untuk membuat keputusan otomatis berdasarkan suatu kriteria data (mirip konsep `if-else` dalam pemrograman).

## 1. Struktur Dasar Fungsi `IF`

Sintaks standar penulisan rumus `IF`:

=IF(Kondisi; Jika_Benar; Jika_Salah)

* **Kondisi**: Syarat atau perbandingan logis yang ingin diuji (contoh: `A1>500`, `B1>=75`).
* **Jika_Benar**: Nilai atau teks yang akan dikeluarkan Excel jika kondisi terpenuhi (*True*).
* **Jika_Salah**: Nilai atau teks yang akan dikeluarkan Excel jika kondisi tidak terpenuhi (*False* / *Else*).

## 2. Aturan Penulisan Teks

* Jika hasil output berupa **teks / kata-kata**, wajib diapit menggunakan tanda kutip dua (`" "` ), contoh: `"Lulus"`, `"Besar"`.
* Jika hasil output berupa **angka**, tidak perlu menggunakan tanda kutip.

## 3. Contoh Implementasi Kasus

* Menguji data apakah suatu nilai lebih besar dari 500:

  =IF(A1>500; "Besar"; "Kecil")
* Formula tersebut dapat ditarik ke bawah menggunakan *AutoFill* (menggunakan *Fill Handle* atau tanda plus kecil di pojok sel) untuk memproses seluruh baris data secara otomatis.
