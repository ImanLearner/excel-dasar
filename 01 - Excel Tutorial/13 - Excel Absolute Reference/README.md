
# 13 - Excel Absolute Reference

Materi khusus mengenai penggunaan referensi sel absolut (Absolute Reference) di Excel untuk mengunci posisi sel.

## Apa itu Absolute Reference?

* **Definisi**: Referensi sel yang dikunci mati menggunakan simbol dolar (`$`) agar **tidak ikut bergeser atau berubah** saat rumusnya disalin atau ditarik ke baris/kolom lain.
* **Karakteristik**: Ditandai dengan simbol `$` pada huruf kolom dan angka barisnya (contoh: `$B$1`).

## Cara Kerja & Simulasi

Saat rumus absolut ditarik ke bawah pada sebuah tabel:

* Kolom atau baris yang diberi tanda `$` akan tetap menunjuk ke sel yang sama persis tanpa ikut turun.
* **Contoh Kasus**: Mengalikan daftar harga barang dengan satu sel persentase pajak tetap yang ada di pojok (`$B$1`).
  * Di baris 10: `=A10 * $B$1`
  * Ditarik ke baris 11 otomatis berubah jadi: `=A11 * $B$1` (sel `A10` turun jadi `A11`, tapi `$B$1` tetap terkunci di tempat).

## Shortcut Cepat

* Cukup tekan tombol **F4** di keyboard saat mengetik atau mengklik nama sel di dalam rumus untuk otomatis menambahkan simbol `$`.
