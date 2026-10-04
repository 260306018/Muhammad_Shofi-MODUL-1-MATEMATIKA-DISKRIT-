# CARA-CARA MENGINSTALL DAN MENJALANKAN PYTHON DI CMD (WINDOWS) ATAU TERMINAL (MACOS)

## 1. Install Python
- **Windows:** unduh dari **python.org/downloads**, lalu **centang "Add python.exe to PATH"** saat instalasi.
- **macOS:** `brew install python` atau unduh dari python.org.
- **Linux:** `sudo apt install python3`

## 2. Cara masuk ke terminal

**Windows**
1. Tekan tombol **Windows**, lalu ketik `cmd`.
2. Klik **Command Prompt**.
3. Cara lain: tekan **Windows + R**, ketik `cmd`, lalu Enter.

**macOS**
1. Tekan **Command + Spasi** untuk membuka Spotlight.
2. Ketik `Terminal`, lalu tekan Enter.

**Linux (Ubuntu/Debian)**
- Tekan **Ctrl + Alt + T**, atau cari "Terminal" di menu aplikasi.

Terminal sudah terbuka jika muncul jendela dengan kursor berkedip di samping alamat folder, misalnya `C:\Users\Nama>` atau `nama@komputer:~$`.

## 3. Cek apakah Python sudah terpasang

**a. Cek versi.** Ketik di terminal lalu tekan Enter:
```bash
python --version
```
Di macOS/Linux, gunakan `python3 --version`.

| Hasil | Artinya |
|---|---|
| `Python 3.x.x` | Python sudah terpasang |
| `'python' is not recognized...` (Windows) | Belum terpasang atau PATH belum dicentang. Instal ulang |
| `command not found` (macOS/Linux) | Belum terpasang, atau coba `python3` |

**b. Uji Boolean tanpa membuat file:**
```bash
python -c "print(True and False)"
```
Jika muncul `False`, Python berjalan dengan benar.
## Penyebab error (paling sering) dan cara mengatasinya
## 1. 'python' is not recognized... (Windows)

Penyebab: Python belum terpasang, atau opsi Add python.exe to PATH tidak dicentang saat instalasi.
Solusi: Instal ulang Python dari python.org dan centang Add python.exe to PATH. Setelah itu tutup CMD, buka lagi, lalu coba python --version.

## 2. command not found (macOS/Linux)

Penyebab: Python belum terpasang, atau perintah yang dipakai salah. Di macOS/Linux, perintahnya python3, bukan python.
Solusi: Gunakan python3 --version. Jika masih gagal, instal dengan brew install python (macOS) atau sudo apt install python3 (Linux).

## 3. NameError: name 'true' is not defined

Penyebab: Menulis true atau false dengan huruf kecil. Di Python harus kapital.
Solusi: Tulis True dan False.

Tambahan: Jika muncul SyntaxError saat membandingkan nilai, periksa apakah Anda memakai = (mengisi nilai) padahal seharusnya == (membandingkan).

## Catatan penting
- Tulis `True` dan `False` dengan huruf kapital.
- `=` untuk mengisi nilai, `==` untuk membandingkan.
- Jika perintah `python` tidak dikenali di Windows, instal ulang dan pastikan **Add python.exe to PATH** dicentang.
