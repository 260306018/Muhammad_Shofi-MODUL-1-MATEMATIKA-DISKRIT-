# TABEL PENGUJIAN

Tabel pengujian digunakan untuk menguji setiap studi kasus dengan beberapa kombinasi kondisi `True` dan `False`.

## 1. Beasiswa - AND

| Nilai Bagus | Rajin | Kelengkapan Dokumen | Hasil |
|---|---|---|---|
| True | True | True | Mendapat BEASISWA |
| True | False | True | Tidak Mendapat BEASISWA |
| False | True | False | Tidak Mendapat BEASISWA |
| False | False | True | Tidak Mendapat BEASISWA |
| False | False | False | Tidak Mendapat BEASISWA |

## 2. Aturan Kelulusan - AND

| Nilai Tinggi | Rajin | Kehadiran | Hasil |
|---|---|---|---|
| True | True | True | Peserta LULUS |
| True | False | True | Peserta Tidak LULUS |
| False | True | False |  Peserta Tidak LULUS |
| False | False | True |  Peserta Tidak LULUS |
| False | False | False | Peserta Tidak LULUS |

## 3. Pesta Kelulusan - AND

| Memiliki Kartu | Memakai Jas | Undangan | Hasil |
|---|---|---|---|
| True | True | True | Boleh Masuk Pesta |
| False | False | True | Tidak Boleh Masuk  Pesta |
| False | True | False | Tidak Boleh Masuk  Pesta |
| False | False | True | Tidak Boleh Masuk  Pesta |
| False | False | False | Tidak Boleh Masuk Pesta |

## 4. Diskon Buku di toko - OR

| Pelajar | Member | Uang | Hasil |
|---|---|---|---|
| True | False | False | Mendapat potongan HARGA |
| False | True | False |  Mendapat potongan HARGA |
| False | False | True |  Mendapat potongan HARGA |
| True | True | False |  Mendapat potongan HARGA |
| False | False | False | Tidak mendapat potongan HARGA | 

## 5. Pesta Pernikahan - OR

| Anggota | Undangan | Keluarga | Hasil |
|---|---|---|---|
| True | False | False | Boleh Mengikuti KEGIATAN |
| False | True | False | Boleh Mengikuti KEGIATAN |
| False | False | True | Boleh Mengikuti KEGIATAN |
| True | True | False | Boleh Mengikuti KEGIATAN |
| False | False | False | Tidak Boleh Mengikuti KEGIATAN |

## 6. Melamar Pekerjaan - OR

| Prestasi | Sertifikat | Kemampuan | Hasil |
|---|---|---|---|
| True | False | False | Mendapat Pekerjaan |
| False | True | False | Mendapat Pekerjaan |
| False | False | True | Mendapat Pekerjaan |
| True | True | False | Mendapat Pekerjaan |
| False | False | False | Tidak Mendapat Pekerjaan |


## 7. Lampu lalu lintas - XOR

| Lampu Hijau | Lampu Merah | Hasil |
|---|---|---|
| True | False | VALID |
| False | True | VALID |
| True | True | Tidak VALID |
| False | False | Tidak VALID |

## 8. Cara Login akun - XOR

| Sandi Benar | OTP benar | Hasil |
|---|---|---|
| True | False | LOGIN BERHASIL |
| False | True | LOGIN BERHASIL |
| True | True | LOGIN GAGAL |
| False | False | LOGIN GAGAL |
