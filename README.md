# Website Portofolio Pribadi — Aura Nasyatul Agisti

Repositori ini berisi kode sumber untuk website portofolio pribadi responsif yang dikembangkan sebagai bagian dari proyek mata kuliah **Pemrograman Web** (Semester 5 Teknik Informatika, STT Pratama Adi).

## 👩‍💻 Profil Pengembang
* **Nama:** Aura Nasyatul Agisti
* **NIM / Kelas:** Teknik Informatika (Semester 5)
* **Institusi:** STT Pratama Adi

---

## 🎨 Palet Warna Portofolio (Soft Elegant)
Desain antarmuka website ini mengusung estetika *Soft Elegant* dengan kombinasi warna berikut:
* **Deep Navy (`#24344D`)** — Warna utama teks dan elemen gelap.
* **Soft Blush White (`#F5F1F2`)** — Warna latar belakang utama.
* **Dusty Rose (`#C08B9B`)** — Warna aksen tombol dan sorotan.
* **Mauve (`#96718E`)** — Warna sekunder untuk efek *hover*.

---

## 🚀 Fitur Utama Website
1. **Salam Otomatis Berdasarkan Waktu:** Menampilkan ucapan selamat (pagi, siang, sore, malam) secara dinamis menggunakan objek `Date` JavaScript.
2. **Efek Mengetik (*Typing Effect*):** Animasi teks bergerak interaktif untuk peran profesional (seperti *Database Enthusiast*, *Web Developer*, dll.).
3. **Mode Gelap / Terang (*Dark/Light Mode*):** Tombol pengalih tema yang menyimpan preferensi pengguna menggunakan `localStorage`.
4. **Filter Proyek Dinamis:** Memungkinkan pengguna menyaring daftar karya berdasarkan kategori (Web Development, Basis Data, Administrasi, dll.).
5. **Validasi Formulir Kontak:** Validasi input nama, email (dengan *Regex*), dan pesan secara interaktif di sisi klien.
6. **Tombol *Back to Top*:** Tombol melayang untuk mempermudah navigasi kembali ke bagian atas halaman.

---

## 🛠️ Teknologi yang Digunakan
* **HTML5 Semantic Elements** (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`)
* **CSS3 & Bootstrap 4** (Grid System, Flexbox, Custom Styling)
* **JavaScript (DOM Manipulation & ES6)**
* **Font Awesome & Google Fonts (Poppins / Montserrat)**

---

## 📂 Struktur Direktori Proyek
```text
/
├── index.html         # Halaman Beranda (Home)
├── about.html         # Halaman Tentang Saya (About)
├── skills.html        # Halaman Keahlian (Skills)
├── experience.html    # Halaman Pengalaman (Experience)
├── portfolio.html     # Halaman Portofolio & Modal Foto
├── contact.html       # Halaman Kontak & Formulir
├── css/
│   └── style.css      # Berkas Pengaturan Gaya & Tema Gelap
└── js/
    └── main.js        # Berkas Logika Interaktif & DOM JavaScript