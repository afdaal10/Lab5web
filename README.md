#  Laporan Praktikum 5 - JavaScript

##  Identitas
| Nama | NIM | Kelas |
|------|-----|--------|
| **Afdhal Agislam** | *(312410445)* | *(TI 24 A5)* |

---

## 🎯 Tujuan Praktikum
1. Mempelajari dasar-dasar penggunaan **JavaScript** pada halaman web.  
2. Menerapkan JavaScript untuk menampilkan **output**, membuat **interaksi pengguna**, serta **memanipulasi elemen HTML (DOM)**.  
3. Menerapkan **logika, kondisi, dan perhitungan** dalam JavaScript.  
4. Membuat **validasi form input** agar data yang dimasukkan pengguna sesuai dengan ketentuan.

---

##  Langkah-Langkah Praktikum

### 1. Persiapan Folder dan File
- Buat folder baru bernama **`lab5_javascript`**.  
- Di dalam folder tersebut buat tiga file utama:

- File `lab5_javascript.html` berisi struktur HTML utama.  
- File `eksternal.js` berisi kode program JavaScript eksternal.  
- File `README.md` digunakan untuk laporan hasil praktikum.

---

### 2. Membuat File HTML Dasar
Tambahkan kode HTML utama dan hubungkan dengan file JavaScript eksternal menggunakan:
```html
<script src="eksternal.js" defer></script>
```
## Gunakan elemen:

Input, Button, dan Select untuk interaksi pengguna.
Div atau Paragraph untuk menampilkan hasil dari JavaScript.

### 3. Menambahkan Script JavaScript Eksternal
Buat file eksternal.js yang berisi berbagai contoh penerapan JavaScript berikut:

# a. Menampilkan output di halaman
```html
document.getElementById("docwrite-target").innerHTML = "<strong>Halo, saya Afdal Agislam!</strong>";
console.log("Hello World dari Afdal Agislam");
```
Menampilkan teks di halaman dan menulis pesan di console browser.

# b. Membuat alert, prompt, dan confirm
```html
alert("Halo! Ini alert dari Afdal Agislam");
const nama = prompt("Masukkan nama Anda:", "Afdal Agislam");
const yakin = confirm("Apakah Anda yakin, Afdal Agislam?");
```
# Fungsi:

- alert() → menampilkan pesan pop-up.
- prompt() → meminta input dari pengguna.
- confirm() → memberikan pilihan OK atau Cancel.
