# 06 - Excel Fill

Materi pembelajaran Excel mengenai otomatisasi pengisian data, manipulasi pola teks, dan pembuatan deret angka tanpa input manual.


## 1. AutoFill (Fill Handle)

Digunakan untuk menduplikasi atau melanjutkan deret data secara otomatis dengan menarik pojok kanan bawah sel (tanda `+` hitam).

* **Angka Berurutan:** Ketik `1` (baris 1) dan `2` (baris 2), blok keduanya lalu tarik ke bawah untuk membuat deret aritmatika otomatis.
* **Hari & Bulan:** Ketik `Senin` atau `Januari`, tarik ke bawah untuk mengisi urutan nama hari atau bulan secara otomatis.
* **Tanggal:** Ketik format tanggal (contoh: `01/09/2026`), tarik ke bawah untuk increment tanggal harian (`+1` hari tiap baris).

## 2. Flash Fill (`Ctrl + E`)

Fitur cerdas Excel berbasis pola untuk memisahkan atau menggabungkan data teks secara instan tanpa rumus.

* **Contoh Memisahkan Teks:**
  * Kolom A: `Udin Sedunia`
  * Ketik manual nama depan di kolom sebelah (`Udin`), lalu tekan **`Ctrl + E`** pada baris berikutnya untuk otomatisasi ke bawah.
* **Contoh Menggabungkan Teks:** Menggabungkan kode ID dan Tahun (`001` + `2026` $\rightarrow$ `001-2026`) dengan mengetik contoh pertama lalu tekan **`Ctrl + E`**.

## 3. Fill Series (Deret Skala Besar)

Digunakan untuk mengisi deret angka dalam jumlah ribuan tanpa harus menarik kursor manual.

1. Ketik angka awal (misal `1`) pada sel pertama.
2. Pilih tab **Home** $\rightarrow$ **Fill** $\rightarrow$ **Series...**
3. Atur pilihan ke **Columns** (untuk ke bawah) atau **Rows** (untuk ke samping).
4. Masukkan batas angka pada **Stop value** (contoh: `10000`).
5. Klik **OK** untuk eksekusi instan.
