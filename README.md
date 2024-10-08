# LIKEEHACK - ADVANCED LIKEE HACKING TOOL (BETA) 🔥
![LikeeHack](https://github.com/user-attachments/assets/f46b8267-a150-4770-918a-ad99694a7628)

**LikeeHack** adalah alat canggih berbasis Python yang dirancang untuk menguji keamanan akun di platform [Likee](https://likee.video/) menggunakan teknik hacking berbasis email. Dengan versi beta ini, kami memberikan kesempatan untuk eksplorasi dan pengujian dalam konteks edukasi. Perhatikan bahwa alat ini hanya untuk tujuan pembelajaran dan tidak untuk aktivitas ilegal.

> 🚨 **Disclaimer**: Alat ini hanya untuk tujuan edukasi. Penyalahgunaan dilarang keras. Kami tidak mendukung aktivitas peretasan atau tindakan ilegal. 🚨

## Prasyarat
- [Python 3.x](https://www.python.org/)
- Modul-modul yang harus diinstal (httpx, rich, dll.)
- [Termux](https://f-droid.org/repo/com.termux_1020.apk)

## Fitur ✨
- 🔍 Kumpulkan Email dari Faker atau Random Generator.
- 📂 Mengelola hasil hacking dalam folder temporary untuk peninjauan lebih lanjut.
- 💻 Menampilkan hasil hacking dengan username, password, dan cookie.
- 📅 Expiry Date: **01 July 2025**.
- 🕵️‍♂️ Hacking akun Likee berdasarkan email yang telah dikumpulkan.

## Instalasi ⚙️
1. Clone repository ini:
    ```bash
    https://github.com/RozhakXD/LikeeHack.git
    ```
2. Masuk ke direktori LikeeHack:
    ```bash
    cd LikeeHack
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Set izin eksekusi pada file `Run`:
    ```bash
    chmod +x Run
    ```   
5. Jalankan program:
    ```bash
    ./Run
    ```

## Cara Menggunakan 🚀
1. Pilih opsi yang sesuai di menu program:
    - Kumpulkan Email melalui Faker, Random, atau berdasarkan Nama.
    - Mulai Hacking dengan memilih file yang berisi daftar email.
    - Lihat Hasil dari upaya hacking yang berhasil.
2. Ikuti instruksi yang diberikan di setiap langkah untuk melanjutkan.

## Proses Hacking 🔓
- **Penanganan Respons**: Jika login berhasil, alat akan menyimpan cookie, UID, dan informasi lainnya untuk referensi lebih lanjut.
- **Pengumpulan Data**: Alat ini mengambil email dan mencoba beberapa kombinasi kata sandi (password brute force).
- **Hashing Password**: Setiap kata sandi di-hash menggunakan algoritma MD5 untuk memastikan keamanan proses.
- **Autentikasi API**: Alat mengirim permintaan POST ke API Likee dengan data yang sudah dikumpulkan dan memeriksa apakah autentikasi berhasil.

## Masalah Umum dan Solusi 💡
1. **Tidak Mendapatkan Hasil**:
    - _Penyebab_: Kata sandi yang dicoba tidak sesuai atau akun target dilindungi dengan kata sandi yang sangat kuat.
    - _Solusi_: Coba gunakan daftar kata sandi yang lebih kuat atau lebih panjang untuk meningkatkan kemungkinan sukses.
2. **IP Terkena Spam**:
    - _Penyebab_: Setelah beberapa kali percobaan login yang gagal, API mungkin mendeteksi alamat IP Anda sebagai spam.
    - _Solusi_: Gunakan mode pesawat untuk mengubah alamat IP Anda, atau gunakan VPN untuk mencegah deteksi lebih lanjut.
3. **Koneksi Jaringan Error Terus**:
    - _Penyebab_: Jaringan internet Anda mungkin tidak stabil atau mengalami gangguan.
    - _Solusi_: Pastikan koneksi internet Anda stabil atau gunakan jaringan lain yang lebih cepat. Jika masih bermasalah, coba ulangi beberapa kali hingga berhasil.
4. **Permintaan Dibatasi (Request Frequency)**:
    - _Penyebab_: Terlalu banyak permintaan yang dikirim dalam waktu singkat.
    - _Solusi_: Tambahkan jeda waktu antara setiap percobaan login atau gunakan alamat IP yang berbeda setelah beberapa percobaan.
5. **Pengiriman Request Gagal**:
    - _Penyebab_: Server Likee mungkin sedang sibuk atau down.
    - _Solusi_: Tunggu beberapa saat dan coba lagi. Jika masalah tetap berlanjut, periksa status server Likee atau gunakan waktu lain untuk mencoba kembali.

## Teknologi yang Digunakan 🛠️
- **Python**: Bahasa pemrograman utama untuk menjalankan script ini.
- **httpx**: Untuk melakukan request HTTP dengan cepat dan efisien.
- **rich**: Untuk mempercantik antarmuka command line dengan panel, warna, dan layout interaktif.

## Tangkapan Layar 📸
![FunPic_20240918-1](https://github.com/user-attachments/assets/fb2a571c-7593-45a0-8b16-44f073e9b521)

![FunPic_20240918-2](https://github.com/user-attachments/assets/f50525c2-9972-43e4-a6ef-111288d7f609)

## Kontribusi 🤝
Proyek ini masih dalam versi beta. Jika Anda menemukan bug atau memiliki ide peningkatan, silakan buat _issue_ atau kirim _pull request_.

## License 📜
This project is licensed under the MIT License - see the [LICENSE](https://github.com/RozhakXD/LikeeHack?tab=MIT-1-ov-file) file for details.
